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

## Table:

{% tabs %}
{% tab title="Get" %}
* get\_visible\_damage
* get\_fakeping
* get\_head\_scale
* get\_quickpeek
* get\_teleport
* get\_override\_damage
* get\_early\_autostop
* get\_autoscope
* get\_pedalowalk
* get\_roll\_safepoints
* get\_force\_baim
* get\_fake\_duck
* get\_double\_tap\_key
* get\_body\_scale
* get\_unsafe\_extrapolation
* get\_recharge\_delay
* get\_minimum\_hitchance
* get\_ignore\_legs
* get\_doubletap
* get\_no\_recharge\_on\_packet\_loss
* get\_damage\_override
* get\_autowall\_damage
* get\_enable
{% endtab %}

{% tab title="Set" %}
* set\_ignore\_legs
* set\_override\_damage
* set\_autoscope
* set\_fakeping
* set\_head\_scale
* set\_visible\_damage
* set\_minimum\_hitchance
* set\_roll\_safepoints
* set\_doubletap
* set\_body\_scale
* set\_enable
* set\_recharge\_delay
* set\_unsafe\_extrapolation
* set\_autowall\_damage
* set\_early\_autostop
* set\_no\_recharge\_on\_packet\_loss
{% endtab %}
{% endtabs %}

##
