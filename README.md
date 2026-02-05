# BASE
Smart contrat on BASE network

📌 Smart Contract
Adresse du contrat : Undisclosed
Réseau : Base Mainnet (https://mainnet.base.org)
Langage : Solidity (^0.8.19)
Fonctionnalités :
Permet à tout utilisateur d'ajouter un message on-chain.
Stocke les messages de manière publique et immutable.
Limite chaque message à 200 caractères pour éviter le spam.

🛠️ Comment Interagir avec le Contrat ?
1️⃣ Via Remix
Ouvrir Remix Ethereum.
Aller dans Deploy & Run Transactions.
Sélectionner "Injected Provider - MetaMask" et choisir le réseau Base Mainnet.
Copier l'adresse du contrat (0x96E76c8A4bd29B962c7285D2DB80a11675028fb6).
Interagir avec les fonctions postNote(string message) et getAllNotes().

2️⃣ Via Etherscan (BaseScan)
Aller sur BaseScan.
Naviguer vers l'onglet "Write Contract" pour ajouter un message.
Aller dans "Read Contract" pour voir tous les messages stockés.
