# Kustomize

Examples for __kustomize__.

The base directory resources will be applied to the current namespace (using ```oc apply -k base```).

For applying the overlays __prod__ or __test__ the namespaces __apache-test__ and __apache-prod__ must exist.
