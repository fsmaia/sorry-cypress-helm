# sorry-cypress-helm

A helm chart for [Sorry Cypress](https://github.com/sorry-cypress/sorry-cypress)

There's no hosted repo for this yet, so you'll have to clone and bake your own:

    git clone https://github.com/tico24/sorry-cypress-helm.git
    cd sorry-cypress-helm
    helm install soz-cypress-test sorry-cypress-helm --dry-run --debug

When you're comfortable, you can ditch the dry-run and the debug.