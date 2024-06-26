The GCP (Google Cloud Platform) command line tool is called `gcloud`. 
It offers a wide range of commands to manage various GCP services. 
Here's a quick rundown of some common commands to get you started:

**Compute Engine:**

* **List VMs:**
    * All VMs: `gcloud compute instances list`
    * VMs with GPUs: `gcloud compute instances list --filter=" GPUs"` (Find specific flags in the documentation)
* **Create a VM:** `gcloud compute instances create [INSTANCE_NAME] --machine-type [MACHINE_TYPE] --zone [ZONE_NAME]` 
* **Details of a VM:** `gcloud compute instances describe [INSTANCE_NAME]`
* **SSH into a VM:** `gcloud compute ssh [INSTANCE_NAME] --zone [ZONE_NAME]` 
* **Create a disk snapshot:** `gcloud compute disks snapshot [DISK_NAME] --snapshot-names [SNAPSHOT_NAME]`

**Cloud Storage:**

* **Create a bucket:** `gsutil mb gs://[BUCKET_NAME]` ([gsutil] is the tool for Cloud Storage)
* **Upload a file to a bucket:** `gsutil cp [LOCAL_FILE_PATH] gs://[BUCKET_NAME]`

**Other Services:**

* **List project ID:** `gcloud config list project`
* **List active account:** `gcloud auth list`
* **List logs:** `gcloud logging logs list`

This is just a small sample. There are many more commands available for different GCP services.  
For a more comprehensive list and details on specific commands, 
refer to the official Google Cloud CLI documentation [https://cloud.google.com/sdk/docs/cheatsheet](https://cloud.google.com/sdk/docs/cheatsheet).

Here are some additional resources that you might find helpful:

* Google Cloud CLI cheat sheet: [https://cloud.google.com/sdk/docs/cheatsheet](https://cloud.google.com/sdk/docs/cheatsheet)
* Introduction to Google Cloud Shell with commands list: [https://www.economize.cloud/guides](https://www.economize.cloud/guides)
