# anotherhelmtest

helm repo add laravel-helm <https://islem-kms.github.io/anotherhelmtest>

helm repo update

helm install first-lh-test laravel-helm/laravel-helm (-f values.yaml)
