<h1 align="center">Columbus Parkour Jam's Official Website</h1>
<p align="center">This is the repository for the official website of the Columbus Parkour Jam, hosted annually in Columbus, Ohio.


<p align="center">https://www.columbuspkjam.com/</p>

### Versions and Branches
Versions are formatted as `<year>.<month>`, and contain development progress largely over the course of their respective month. For example, the version `2024.10` largely corresponds to development occurring throughout October, 2024. Versions are attempted to be cut off at the beginnning of each month, but may be delayed if something going into a previous version is still in-progress.

The `main` branch corresponds to the in-progress version's (i.e., the current month) source code, while the `prod` branch corresponds the the in-progress version's deployment-ready build.

Source code for previous versions can be found in branches formatted as `versions/<version>` (for example, `versions/2024.10`), while deployment-ready builds for previous versions can be found in branches formatted as `builds/<version>` (for example, `builds/2024.10`). These branches are cut off of `main` and `prod` respectively, at the same time when work on the next version begins.

### Deployment
Deployment is done using GitHub Pages with HTTPS and a custom domain name. GitHub Pages will use the most recent `builds/<version>` branch when deploying (i.e., the newest "finished" version - one version prior to the current in-progress version).
