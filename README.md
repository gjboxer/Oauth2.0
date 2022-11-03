## Google Calendar API OAuth 2.0 for Web Server Applications Integration - Django Rest Framework

For run this project on a local machine: 

```sh
pip install - r requriments.txt
```

- Endpoint:
```
/rest/v1/calendar/init/ -> GoogleCalendarInitView()
```
This view should start step 1 of the OAuth. Which will prompt user for his/her credentials

```
/rest/v1/calendar/redirect/ -> GoogleCalendarRedirectView()
```

## Documents and References

| Name | Sources |
| ------ | ------ |
| Google Identity: Using OAuth 2.0 for Web Server Applications | [/identity/protocols/oauth2/web-server][PlDb] |
| Google Calendar API | [/calendar/api/v3/referenc][PlGh] |
| Google Account Credentials| [/identity/protocols/oauth2/web-server#exchange-authorization-code][PlIa] |


[PlDb]: <https://developers.google.com/identity/protocols/oauth2/web-server>
[PlGh]: <https://developers.google.com/calendar/api/v3/reference>
[PlIa]: <https://developers.google.com/identity/protocols/oauth2/web-server#exchange-authorization-codee>
