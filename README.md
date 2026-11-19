# patchpilot-demo

Deliberately vulnerable target repo for [PatchPilot](https://github.com/nourahaddaoui/patchpilot).
`requirements.txt` pins `requests==2.25.1` (CVE-2023-32681, CVE-2024-35195, CVE-2024-47081).
Do not use in production. Reset to the vulnerable state with the `baseline` tag.
