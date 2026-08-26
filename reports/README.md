# PDF reports

Place PDFs in this folder, for example:

```text
reports/
  primordial-black-holes.pdf
  neutron-absorption.pdf
```

Then replace the placeholder in `index.html` with an object element:

```html
<object data="reports/primordial-black-holes.pdf" type="application/pdf" aria-label="Primordial black holes report">
  <p>PDF preview unavailable. <a href="reports/primordial-black-holes.pdf">Download the report.</a></p>
</object>
```

Keep a normal link to each PDF so visitors on browsers without embedded PDF support can still open or download it.
