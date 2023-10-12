# API SEQINO

Bienvenue sur l'API SEQINO ! Il s'agit d'un environnement public où vous pouvez tester et comprendre comment fonctionnent nos routes API avant de les intégrer dans votre application. Cette API propose une réplique entièrement fonctionnelle de notre environnement en direct, avec des limites modulées pour garantir une utilisation équitable.
URL de l'API : https://api.seqino.dev.

## Authentification
Le système d'authentification utilisé est l'authentification Bearer. Vous devrez utiliser votre token de test d'entreprise (JWT) que vous devrez inclure dans l'en-tête Authorization de vos requêtes HTTP vers l'API.

## Utilisation
### POST /invoices
> Creation d'une facture au format Factur-x XML. Si les données JSON reçu dans le corps de la requête sont validées, le JSON est converti en en Factur-x

## Support
Si vous rencontrez des problèmes ou avez des questions, n'hésitez pas à contacter notre équipe support via support@seqino.com.

## Documentation
Pour plus d'informations détaillées sur l'API, veuillez vous référer à notre documentation : https://seqino.github.io/api-doc/.
