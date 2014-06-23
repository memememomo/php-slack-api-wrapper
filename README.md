# API

https://api.slack.com/


# Requirements

- curl (in Snoopy for HTTPS)


# SYNOPSYS


```
require_once 'src/Slack.php';

$token = 'Slack-Token';

$slack = new Slack($token);

// User List
$res = $slack->user_list();
var_dump($res['members']);
```
