# How to install CORS proxy to Vercel

*Updated: 2025-03-12*

## 1. Register free Vercel account

[Vercel][vercel] provides free hosting.

## 2. Fork this GitHub repository

Vercel won't operate without a bound GitHub (GitLab/Bitbucket) account.
So you have to fork this repository to your GitHub account.

| № | Step | Screenshot |
|---|---   |---         |
| 1 | Press `Fork` | ![Fork][fork-01] |
| 2 | Press `Create fork` | ![Create fork][fork-02] |
| 3 | Wait | ![Wait][fork-03] |
| 4 | Done | ![Done][fork-04] |

## 3. Create Vercel project

| № | Step | Screenshot |
|---|---   |---         |
| 1 | Press `Add New... -> Project` | ![Add new project][create-01] |
| 2 | Press `Add GitHub Account` | ![Add GitHub account][create-02] |
| 3 | Select GitHub account to install Vercel into | ![Select GitHub account][create-03] |
| 4 | Grant Vercel access to the forked repository | ![Grant access][create-04] |
| 5 | Press `Import` | ![Import][create-05] |
| 6 | Press `Deploy` | ![Deploy][create-06] |
| 7 | Wait | ![Wait][create-07] |
| 8 | Done | ![Done][create-08] |

## 4. Verify CORS proxy is working

| № | Step | Screenshot |
|---|---   |---         |
| 1 | Open `Domains` link | ![Link][verify-01] |
| 2 | Make sure `Isomorphic-Git CORS proxy` is displayed | ![Root][verify-02] |

[create-01]: readme/create-01.png
[create-02]: readme/create-02.png
[create-03]: readme/create-03.png
[create-04]: readme/create-04.png
[create-05]: readme/create-05.png
[create-06]: readme/create-06.png
[create-07]: readme/create-07.png
[create-08]: readme/create-08.png
[fork-01]: readme/fork-01.png
[fork-02]: readme/fork-02.png
[fork-03]: readme/fork-03.png
[fork-04]: readme/fork-04.png
[vercel]: https://vercel.com
[verify-01]: readme/verify-01.png
[verify-02]: readme/verify-02.png
