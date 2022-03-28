LAB - TAP Sample
=====================

This is an example Learning Lab created by Jeremy and Mae

If you already have the Educates operator installed and configured, to
deploy and view this sample workshop, run:

```
kubectl apply -f https://raw.githubusercontent.com/x95castle1/lab-tap-sample/master/resources/workshop.yaml
kubectl apply -f https://raw.githubusercontent.com/x95castle1/lab-tap-sample/master/resources/training-portal.yaml
```

This will deploy a training portal hosting just this workshop. To get the
URL for accessing the training portal run:

```
kubectl get trainingportal/lab-markdown-sample
```

The training portal is configured to allow anonymous access. For your own
workshop content you should consider removing anonymous access.
