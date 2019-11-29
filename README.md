# istio-tests
to enable auto injetion of istio envoy proxy side car to pods of default namespaces use below command
kubectl label namespace default istio-injection=enabled
