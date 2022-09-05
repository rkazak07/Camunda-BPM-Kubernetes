# camunda-bpm-kubernetes
camunda-bpm-kubernetes-deploy

# values Dosyasındaki image'ı ihtiyaç halinde değiştirebilirsiniz.
# ingress.yaml dosyamızı host vs tls ayarlamanızı yapabilirsiniz.

## Öncelikle Namespace oluşturuyoruz.
```
kubectl create ns camunda-bpm
```
## 'values.yaml' dosyamızı düzenliyoruz.

```
kubectl apply -f values.yaml -n camunda-bpm
```
## ingress.yaml dosyasınız deploy ediyoruz.

```
kubectl apply -f ingress.yaml -n camunda-bpm
```
