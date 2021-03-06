# gcloud

- Connect to google cloud project from cloud shell ( gcloud config set project PROJECT_ID ) 
- Connect to cloud vm ( gcloud compute ssh [USER@]INSTANCE [--command=COMMAND] [--container=CONTAINER] [--dry-run] [--force-key-file-overwrite] [--plain] [--ssh-flag=SSH_FLAG] [--ssh-key-file=SSH_KEY_FILE] [--strict-host-key-checking=STRICT_HOST_KEY_CHECKING] [--zone=ZONE] [--internal-ip     | --tunnel-through-iap] [--ssh-key-expiration=SSH_KEY_EXPIRATION     | --ssh-key-expire-after=SSH_KEY_EXPIRE_AFTER] [GCLOUD_WIDE_FLAG …] [-- SSH_ARGS … )
- Create instance ( gcloud compute instances create gcelab2 --machine-type n1-standard-2 --zone us-central1-f )
- List projects ( gcloud config list project ) 
- Check default zone ( gcloud config get-value compute/zone )
- Check default region ( gcloud config get-value compute/region )
- Identify project info ( gcloud compute project-info describe --project PROJECT_ID )
- Instances create help ( gcloud compute instances create --help )
- Help ( gcloud -h )
- Config help ( gcloud config --help )
- View the list of configurations in your environment ( gcloud config list )
- View To see all config properties and their settings( gcloud config list --all )
- Listing Components ( gcloud components list )
- Interactive mode ( gcloud beta interactive )
- Create cluster ( gcloud container clusters create CLUSTER_NAME )
- Get authentication credentials for the cluster ( gcloud container clusters get-credentials [CLUSTER-NAME] )
- Deploy an application to the cluster ( kubectl create deployment hello-server --image=gcr.io/google-samples/hello-app:1.0 )
- Expose kubernetes ( kubectl expose deployment hello-server --type=LoadBalancer --port 8080 )
- Inspect kubernetes service ( kubectl get service )
- Delete cluster ( gcloud container clusters delete [CLUSTER-NAME] )
- Create firewall ( gcloud compute firewall-rules create www-firewall-network-lb --target-tags network-lb-tag --allow tcp:80 )
- List Instances ( gcloud compute instances list )
- Create static IP ( gcloud compute addresses create network-lb-ip-1 --region us-central1 )
   
