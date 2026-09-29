# Studexa Maths

Static functional prototype matching the Studexa dashboard mock-up style.

- `index.html` — student dashboard
- `teacher.html` — teacher dashboard, class management and homework builder
- `data/curriculum.json` — 500 generated curriculum nodes (100 per Year 7–11)
- `data/homeworks.json` — 1000 premade homework metadata records

The homework builder supports individual dates, generating a weekly date series, deleting individual dates, Year 10/11 tier filters, and the EXTRA support label.

Years 10–11 use Pearson Edexcel GCSE tags; Years 7–9 are described as Pearson-aligned KS3 progression rather than as an Edexcel GCSE specification. The supplied questions/homework metadata are original Studexa demo content, not copied Pearson questions.

For a real deployment, connect this app to the shared Supabase schema included in the Studexa Learning ZIP.
