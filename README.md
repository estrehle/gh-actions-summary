# GitHub Actions Summary

Sometimes you want to see the output from a lot of GitHub Actions jobs, for example when running tests or applying infrastructure changes.
It is tedious to go through each job's output separately.
With the GitHub Actions _job summary_ it is possible to see all job outputs in one place.

This repo is a minimum working example for using the job summary.
The [summary_demo.yml](./.github/workflows/summary_demo.yml) workflow runs 3 jobs that create console output and send it to the job summary as formatted markdown.
The result looks like this:
![image](https://user-images.githubusercontent.com/20908872/223998549-0d21b7dd-23fa-4b04-be1e-3f6eb1e2b99b.png)
