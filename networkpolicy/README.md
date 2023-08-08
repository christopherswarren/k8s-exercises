This folder contains two yaml documents that will deploy nginx along with a network policy.

1. What cluster configuration prerequisites must be in place to use this network policy?

2. How could a pod connect to the nginx service with the policy applied?<br>
_NOTE_<br>
You can run a pod to test the connection using the following command:<br>
`kubectl run busybox --image=busybox --rm -it --restart=Never -- wget -O- http://nginx:80 --timeout 2`