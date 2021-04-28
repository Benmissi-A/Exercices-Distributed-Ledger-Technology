# Exercices Distributed Ledger Technology
---

#
#
#### - question 1
##### dans le cas ou le nombre de transactions dans le Block à valider est impair la derniere transaction est dupliquée ##### et "hashee" avec elle meme.
#
#
If there are an odd number of nodes on any level of the merkle tree, the last node is duplicated and hashed with itself.n
If there were a Tx4, the diagram would look like this

                      Root (Hash01234444)               
                   /                      \             
            Hash0123                 Hash4444|
            /      \                    /     \ 
       Hash01      Hash23           Hash44     Hash44
       /   \        /   \             /   \
    Hash0  Hash1  Hash2  Hash3     Hash4   Hash4
    
https://bitcoin.stackexchange.com

  
#### - question 2
##### selon ma source un noeud arrive à retrouver ses paires et a rejoindre le reseau en a laide d'une liste d'adresses ip
##### issues de ses precedentes conexions
##### cela dit cette methode pose probleme lors de sa premiere connexion 
##### il passe alors par un DNS seed qui est un server contenant une liste d'adresses ip de paires
https://bitcoin.stackexchange.com
#
#
#### - question 3
##### Gavin Andresen est le scientifique en chef de la Fondation Bitcoin.
##### et "hashee" avec elle meme.
#
#
#### - question 4
##### les differents blocs se connectent les un aux autres par adresse ip pour former des chaines de verification
#
#

#### - question 5
##### la structure de donnée qui represente le mieux la blockchan est la Linked_list
https://en.wikipedia.org/wiki/Linked_list
#### - question 6
##### non ,  si on modifie la transaction sela modifie le hash dans le header du bloc
##### celui-ci ne correspond pas a celui du block suivant et la transaction echoue

