# k8s-Practice

# Run this command in order to run all the kubernetes Menifest at once...

k apply -f configMap_Secrets_Deployment.yaml,deployment.yaml,hpa-Deployment.yaml,jobs_cronjobs_InitContainer.yaml,namespace_ResourceQuota_limitRange.yaml,pod_annotations_labels_ports_args_env_volumeMounts_resources_livenessProbe_restartPolicy_nodeSelector.yaml,pv_pvc_deployment.yaml,RC_replicas_equalityBasedSelectors.yaml,RS_setBasedSelectors.yaml,service+deployment.ya


# Run this command in order to delete all the kubernetes Menifest at once...

k delete -f configMap_Secrets_Deployment.yaml,deployment.yaml,hpa-Deployment.yaml,jobs_cronjobs_InitContainer.yaml,namespace_ResourceQuota_limitRange.yaml,pod_annotations_labels_ports_args_env_volumeMounts_resources_livenessProbe_restartPolicy_nodeSelector.yaml,pv_pvc_deployment.yaml,RC_replicas_equalityBasedSelectors.yaml,RS_setBasedSelectors.yaml,service+deployment.yaml
