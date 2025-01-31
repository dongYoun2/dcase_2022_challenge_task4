# DCASE 2022 Challenge Task 4
Domestic environment sound event detection task.
- implementation of [DCASE 2022 Challenge Task 4](https://dcase.community/challenge2022/task-sound-event-detection-in-domestic-environments)'s [DATA ENGINEERING FOR NOISY STUDENT MODEL IN SOUND EVENT DETECTION](https://dcase.community/documents/challenge2022/technical_reports/DCASE2022_Suh_120_t4.pdf) Technical Report.
- The code is approved by [Return Zero](https://www.rtzr.ai/en) to be revealed on GitHub by removing internal file paths and commit logs.
- articles on [aitimes.kr](https://www.aitimes.kr/news/articleView.html?idxno=25537), [etoday.co.kr](https://www.etoday.co.kr/news/view/2181689)

![image](docs/aug_pipeline.png)

**Results**
![image](docs/results.png)

---

## DCASE Task 4
Baseline DCASE Task 4 recipes:
- [DCASE 2021 Task 4](./recipes/dcase2021_task4_baseline)
- [DCASE 2022 Task 4](./recipes/dcase2022_task4_baseline)

Updates on the [website][dcase_website] and [join us][invite_dcase_slack] in the dedicated
[slack channel][slack_channel].


[dcase_website]: https://dcase.community
[desed]: https://github.com/turpaultn/DESED
[fuss_git]: https://github.com/google-research/sound-separation/tree/master/datasets/fuss
[fsd50k]: https://zenodo.org/record/4060432
[invite_dcase_slack]: https://join.slack.com/t/dcase/shared_invite/zt-mzxct5n9-ZltMPjtAxQTSt3a6LFIVPA
[slack_channel]: https://dcase.slack.com/archives/C01NR59KAS3

## Installation Notes

### You want to run a recipe or DCASE Task 4 baseline system

Go to `./recipes/YOUR_DESIRED_RECIPE` and follow the instructions there in the `README.md`

In each recipe we provide a conda script which creates a suitable conda environment with all dependencies, including
**pytorch** with GPU support in order to run the recipe. There are also instructions for data download and preparation.


### You need only desed_task package for other reasons
Run `python setup.py install` to install the desed_task package


## Your own recipes ?
If you want to share your recipe in this repo, do not hesitate to create a pull request.
To be able to contribute/modify the code install `desed_task` via `python setup.py develop`.


### Note

By default a `pre-commit` is installed via `requirements.txt`.
The pre-commit hook checks for **Black formatting** on the whole repository.
Black ensures that code style is consistent through the whole repository and recipes for better readability.


