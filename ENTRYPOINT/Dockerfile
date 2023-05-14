### Entrypoint is also used to run the container like CMD, But there are few differences.
### we can't override the ENTRYPOINT, but we can override with CMD.
### we can't override ENTRYPOINT, if you try to do that, it will append to the ENTRYPOINT command.
FROM almalinux
# #CMD [ "ping", "-c5","google.com" ]
# ENTRYPOINT [ "ping","-c5","google.com" ]

## comibined
CMD [ "google.com" ]
ENTRYPOINT [ "ping","-c5" ]