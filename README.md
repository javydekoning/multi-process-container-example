# multi-process-container-example

Simple container running httpd and cron using supervisor.

In this example there is a webserver running (`httpd`).
A cron is running (in non-daemonized mode), which does a `GET` request every minute.