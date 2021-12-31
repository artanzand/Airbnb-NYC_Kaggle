# Airbnb NYC - Kaggle mini project
I will be implementing supervised machine learning on the NYC Airbnb [data](https://www.kaggle.com/dgomonov/new-york-city-airbnb-open-data) from Kaggle using ensemble models alongwith feature engineering and model selection. For this I will be using cleaned data acquired from Kaggle while walking through my analysis in an `.ipynb` file. Details about the dataset is provided in the notebook and below I will mention the machine learning techniques I will be using in this project. 


## New York City Airbnb Open [data](https://www.kaggle.com/dgomonov/new-york-city-airbnb-open-data)
`Golden Rule`


<br>

# To use this repo
Clone this Github repository, install the dependencies, and run the 
following commands at the command line/terminal from the root directory of the project:

```
conda env create --file env.yaml
conda activate Kaggle_projects
```
## Setting up Kaggle API
To use the Kaggle API, sign up for a Kaggle account at https://www.kaggle.com. Then go to the 'Account' tab of your user profile (https://www.kaggle.com/<username>/account) and select 'Create API Token'. This will trigger the download of kaggle.json, a file containing your API credentials. Place this file in the location `~/.kaggle/kaggle.json`. I have already included the `kaggle` package in the repo environment, and running the below script should download the required files. 

## To download the data files
Run the following commands at the command line/terminal from the root directory of the project to download the data files in a `/downloads` folder:
```
python src/download_data.py --dataset=dgomonov/new-york-city-airbnb-open-data --file_path=downloads/
```

You can now run the notebook file.


# To contribute to the repository:
1. Fork the repository.
2. Add the implementation of the algorithm with a clearly defined filename for the script or the notebook.
3. Test the implementation thoroughly and make sure that it works with some dataset.
4. Add a link with a short description about the file in the [README.md](https://github.com/artanzand/Kaggle_projects/blob/main/README.md).
5. Create a pull request for review with a short description of your changes.
6. Do not forget to add attribution for references and sources used in the implementation.
