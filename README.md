# Appointment cancellation detector

👋 **Make sure that you exported your personal environment variables on your local terminal**. Especially, you need:

* `MLFLOW_TRACKING_URI`
* `AWS_ACCESS_KEY_ID`
* `AWS_SECRET_ACCESS_KEY`


Our advice is to create a `secrets.sh` or `secrets.ps1` file containing:

```bash
export MLFLOW_TRACKING_URI="REPLACE_WITH_YOUR_MLFLOW_TRACKING_URI";
export AWS_ACCESS_KEY_ID="REPLACE_WITH_YOUR_AWS_ACCESS_KEY_ID";
export AWS_SECRET_ACCESS_KEY="REPLACE_WITH_YOUR_AWS_SECRET_ACCESS_KEY";
```

```ps1
$env:MLFLOW_TRACKING_URI="REPLACE_WITH_YOUR_MLFLOW_TRACKING_URI";
$env:AWS_ACCESS_KEY_ID="REPLACE_WITH_YOUR_AWS_ACCESS_KEY_ID";
$env:AWS_SECRET_ACCESS_KEY="REPLACE_WITH_YOUR_AWS_SECRET_ACCESS_KEY";
```

You can then simply run `source secrets.sh` OR `./secrets.sh`to export all your environmnet variables at once.


launch `mlflow run  https://github.com/2nzi/MLflowProject-Train.git -A gpus=all` to tri the github.

