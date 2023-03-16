# auto-slack-message
A Github Actions to send automatic message to Slack

## Inputs

### `slack_webhook`
**Required** The slack webhook

### `message`
The message you are sending. Default `Auto Message to you from github action`


## Output

### `response`
Message Sent Successfully.!!!

## Example usage

```
uses: Millz147/auto-slack-message@v1
with:
  slack_webhook: 'https://slackwebhook.com/api/expanle'
  message: 'hello i just push/pull'
```
