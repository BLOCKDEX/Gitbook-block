---
cover: ../../.gitbook/assets/charts-gea28046f3_1920(1).jpg
coverY: 0
---

# Trading Rules

{% hint style="info" %}
#### Since our smart contract fund pool is designed to be very flexible, each smart contract fund pool can be freely selected by the initiator of the calling contract
{% endhint %}

<table data-column-title-hidden data-view="cards"><thead><tr><th align="center"></th><th align="center"></th><th data-hidden></th><th data-hidden data-card-target data-type="content-ref"></th></tr></thead><tbody><tr><td align="center"><strong>Billing Cycle</strong></td><td align="center"><p></p><p>50 Blocks (100s)</p></td><td></td><td></td></tr><tr><td align="center"> <strong>B</strong></td><td align="center">The number at the end of the block hash is 0~4</td><td></td><td></td></tr><tr><td align="center"> <strong>L</strong></td><td align="center">The number at the end of the block hash is 5~9</td><td></td><td></td></tr><tr><td align="center"><strong>Correct</strong></td><td align="center">+1%,+5% ,+10%,+15%,+20%</td><td></td><td></td></tr><tr><td align="center"><strong>Wrong</strong></td><td align="center">-1%,-5%<br>,-10%,-15%,-20%</td><td></td><td></td></tr><tr><td align="center"><strong>Fee</strong></td><td align="center"><mark style="color:blue;"></mark><a href="fees.md"><mark style="color:blue;">Click</mark></a> <mark style="color:red;"></mark> to see more</td><td></td><td><a href="fees.md">fees.md</a></td></tr></tbody></table>



{% hint style="warning" %}
#### If the block of the user's current transaction contract is at the block height ending in 49/50/99/multiples of 100, the settlement result of the transaction will be settled at the block height of the next cycle
{% endhint %}
