# linode-cli nodebalancers

> Beheer Linode NodeBalancers.
> Bekijk ook: `linode-cli`.
> Meer informatie: <https://techdocs.akamai.com/cloud-computing/docs/cli-commands-for-nodebalancers>.

- Toon alle NodeBalancers:

`linode-cli nodebalancers list`

- Maak een nieuwe NodeBalancer:

`linode-cli nodebalancers create --region {{regio}}`

- Toon details van een specifieke NodeBalancer:

`linode-cli nodebalancers view {{nodebalancer_id}}`

- Update een bestaande NodeBalancer:

`linode-cli nodebalancers update {{nodebalancer_id}} --label {{nieuw_label}}`

- Verwijder een NodeBalancer:

`linode-cli nodebalancers delete {{nodebalancer_id}}`

- Toon alle configuraties voor een NodeBalancer:

`linode-cli nodebalancers configs list {{nodebalancer_id}}`

- Voeg een nieuwe configuratie toe aan een NodeBalancer:

`linode-cli nodebalancers configs create {{nodebalancer_id}} --port {{poort}} --protocol {{protocol}}`
