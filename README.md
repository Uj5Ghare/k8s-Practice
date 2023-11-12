# k8s-Practice
- These all are my Kubernetes practice files.
- There is all in these files, I learnt from my kubernetes learning journey.
- I made this project for my own and also for needed persons means I can use this files as template and make changes in these files and create a new Menifest.
- By using following 2 commands we can create or delete all K8s Menifests at once.


## Run this command in order to run all the kubernetes Menifest at once...

`k apply -f configMap_Secrets_Deployment.yaml,deployment.yaml,hpa-Deployment.yaml,jobs_cronjobs_InitContainer.yaml,namespace_ResourceQuota_limitRange.yaml,pod_annotations_labels_ports_args_env_volumeMounts_resources_livenessProbe_restartPolicy_nodeSelector.yaml,pv_pvc_deployment.yaml,RC_replicas_equalityBasedSelectors.yaml,RS_setBasedSelectors.yaml,service+deployment.yaml`


## Run this command in order to delete all the kubernetes Menifest at once...

`k delete -f configMap_Secrets_Deployment.yaml,deployment.yaml,hpa-Deployment.yaml,jobs_cronjobs_InitContainer.yaml,namespace_ResourceQuota_limitRange.yaml,pod_annotations_labels_ports_args_env_volumeMounts_resources_livenessProbe_restartPolicy_nodeSelector.yaml,pv_pvc_deployment.yaml,RC_replicas_equalityBasedSelectors.yaml,RS_setBasedSelectors.yaml,service+deployment.yaml`
