<h2><img src="https://camo.githubusercontent.com/be37cdc8f930300096c506ad4574eaae977c48fbb2705cfcb92f4eeab8282c7a/68747470733a2f2f6d656469612e67697068792e636f6d2f6d656469612f56674344417a634b767352364f4d307557672f67697068792e676966" style="width: 40px; display: inline-block;"> A little more about me...</h2>

```
if (!empty($_SESSION['soul'])) {
    if ($_SESSION['soul'] == "machine") {
        if ($body['brain'] == "over") {
            echo "nocturnal";
        } else {
            echo "enjoyed";
        }
    } else if ($_SESSION['soul'] == "human") {
        if ($body['brain'] == "relaxed") {
            echo "enjoyed";
        } else {
            echo "nocturnal";
        }
    } else {
        echo "dead";
    }
} else {
    echo "nothing";
}
```
