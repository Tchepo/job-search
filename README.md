# job-search

```bash
xelatex.exe resume.tex ; mv resume.pdf "resume_$(date +%Y-%m-%d)_$((10#$(date +%H)*60 + 10#$(date +%M)))_$(git rev-parse --short origin/main).pdf"
```
That will create for example `resume_2025-10-31_582_50508bb.pdf`

- date : `2025-10-31`
- minutes since midnight : `582`
- last commit on the main : `50508bb`
