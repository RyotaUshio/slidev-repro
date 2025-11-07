---
theme: default
transition: slide-left
layout: default
---

# This works

<div>
  <div>

  - A
  - B

  </div>
</div>

---

# This also works

<div>
<div>

- A
- B

</div>
</div>

---

# However, this does not work

`prettier-plugin-slidev` transforms the first slide content to the following, but it causes an error.

<div>
  <div>

- A
- B

  </div>
</div>
