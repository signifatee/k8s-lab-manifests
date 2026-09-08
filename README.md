# k8s-lab-manifests
Манифесты для деплоя приложений и сервисов на лабораторный стенд

kubectl apply -f root/root-app.yaml

Схема: app of apps

root -> папка для root application

apps -> папка с приложениями
syncPolicy: automated

manifests -> папка с манифестами для применения
