node-red-contrib-slack
========================

A <a href="http://nodered.org" target="_new">Node-RED</a> node to post messages to  <a href="http://www.slack.com/" target="_new">Slack</a>.

Install
-------

Run the following command in the root directory of your Node-RED install:

    npm install node-red-contrib-slack


Usage
-----

## Slack Incoming Webhook
<i><a href="http://www.slack.com" target="_new">Slack</a></i> output node.

Expects a <b>msg.payload</b> with a string that will be posted to the channel.

### Webhook URL
This can be found on the Incoming WebHooks for the channel of your choice.
### Username
This is the name that will appear above each post to the channel
### Emoji Icon
This is the emoji that will be dispalyed next to each of the messages in the channel.
All possible Emoji icons can be found at <i><a href="http://emoji-cheat-sheet.com" target="_new">Emoji Cheat Sheet</a></i>
### Destination channel
You can optionally override the destination channel if required - either in the edit dialogue or by setting <b>msg.channel</b>.
### Attachments
You can also create <a href="https://api.slack.com/docs/attachments" target="_new">Slack attachments</a> by adding a <b>msg.attachments</b> property that must be an array.

For more information see <i><a href="https://api.slack.com/incoming-webhooks" target="_new">Slack Incoming Webhooks</a></i>.

## Slack Outgoing Webhook
<i>Work in progress</i>