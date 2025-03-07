# Usage

[Helm](https://helm.sh) must be installed to use the charts.  Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:

    helm repo add ans-service https://ans-service.github.io/helm-charts
    
To install the mainchart chart:

    helm install my-<chart-name> ans-service/mainchart   
    
To install the multichart chart:

    helm install my-<chart-name> ans-service/multichart       

To uninstall the chart:

    helm delete my-<chart-name>
    
If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages.  
You can run `helm search repo anscharts` to see the charts.
