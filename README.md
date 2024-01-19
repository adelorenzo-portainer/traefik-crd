## Deployment of CRD with Portainer using GitOps

1) Select Applications from the Menu on the left ![Screenshot 2024-01-18 at 11 22 22 PM](https://github.com/adelorenzo-portainer/traefik-crd/assets/81579885/32407411-f186-4c78-8856-99fe97fdd3cb)

2) Add the details to the Manifest deployment accordingly:
  - Use namespace(s) specified from manifest  
  - Name: __traefik-crd__ 
  - Repository URL: __https://github.com/adelorenzo-portainer/traefik-crd__
  - Repository reference: __refs/head/main__
  - Manifest path: __traefik-crd-complete.yaml__
![Screenshot 2024-01-18 at 11 22 45 PM](https://github.com/adelorenzo-portainer/traefik-crd/assets/81579885/d0de83c2-bf28-47aa-8308-59c52230515d)

3) Make sure to enable GitOps updates with:
  - Mechanism: Webhook
  - Always apply manifest
![Screenshot 2024-01-18 at 11 23 04 PM](https://github.com/adelorenzo-portainer/traefik-crd/assets/81579885/7023b2c2-c185-4e33-a847-657cbcb7b448)



