# 2. Architecture et etat

L architecture separe les contrats de coordination, les actifs, les bibliotheques et les adaptateurs. Les fonctions publiques modifient un etat durable, tandis que les vues reconstruisent les positions et les droits. Les integrations doivent suivre les evenements et les erreurs, pas seulement supposer un transfert reussi. Le depot source expose notamment Credit Accounts, Credit Manager, adapters, quotas, diesel tokens, liquidation.

[Chapitre suivant : flux principal](03-flux-principal.md)
