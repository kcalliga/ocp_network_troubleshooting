For the pod-to-pod network troubleshooting exercise, we will create a project called pod-to-pod and then create two instances of the httpd pod (httpd1 and httpd2)

Run the following commands for this exercise

1.  oc create project pod-to-pod
2.  oc create -f httpd1.yaml
3.  oc create -f httpd2.yaml
4.  To ensure that both pods created successfully, run oc get po

