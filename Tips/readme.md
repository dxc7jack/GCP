# Tips

## Using This Repository
- Each notebook that has a parameter defined as `BUCKET = PROJECT_ID` can be customized:
    - change this to `BUCKET = PROJECT_ID + 'suffix'` if you already have a GCS bucket with the same name as the project.  

## Notes
- [`aiplatform` Python Client](./aiplatform_notes.md)
    - All about the Vertex AI Python Client: versions (`aiplatform_v1` and `aiplatform_v1beta`) and layers (`aiplatform` and `aiplatform.gapic`).  Includes the deeper details and examples of using each.

## Notebooks
- [Python Multiprocessing](./Python%20Multiprocessing.ipynb)
    - tips for executing multiple tasks at the same time
- [Python Job Parameters](./Python%20Job%20Parameters.ipynb)
    - tips for passing values to programs from the command line or with files
- [Python Client for Cloud Build](./Python%20Client%20for%20Cloud%20Build.ipynb)
    - tips for building derivative containers
- [Python Client for GCS](./Python%20Client%20for%20GCS.ipynb)
    - tips for interacting with GCS storage from Python, Vertex AI
    
## Additional Tips
- Tips for working with the Python Client for BigQuery can be found here:
    - [03 - Introduction to BigQuery ML (BQML)](../03%20-%20BigQuery%20ML%20(BQML)/03%20-%20Introduction%20to%20BigQuery%20ML%20(BQML).ipynb)
    
