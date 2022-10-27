# 🔫 menu\_ragebot

## Functions

### set\_

`set_(bool/float):` <mark style="color:purple;">`void`</mark>

### get\_

`get_:` <mark style="color:purple;">`bool/float`</mark>

{% hint style="info" %}
for the weapon tabs in the ragebot you need to:

include the tab FIRST in the function

SCAR = 0, SCOUT = 1, AWP = 2 ...
{% endhint %}

{% tabs %}
{% tab title="Example:" %}
menu\_ragebot.get\_minimum\_hitchance(0)  --for getting the scar hitchance

menu\_ragebot.set\_minimum\_hitchance(0, 100)  --for setting the scar hitchance to 100
{% endtab %}
{% endtabs %}
