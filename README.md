# k8s-lab-manifests
Манифесты для деплоя приложений и сервисов на лабораторный стенд

kubectl apply -f root/platform.yaml
kubectl apply -f root/labs.yaml

Схема: app of apps

root -> папка для root application

apps -> папка с приложениями
apps/platform -> syncPolicy: automated
apps/labs -> syncPolicy: manual 

platform -> для постоянных приложений
labs -> для экспериментов и временных приложений

manifests -> папка с манифестами для применения
