# Circular dependency error

This is a demonstration of how to provoke the circular dependency error when using namespaced concerns
with Rails 4.

## HowTo

1) Start server, visit the page (you get the raise message)
2) Reload the page (you get Circular dependency warning)
3) comment out the raise and reload the page (ruby process hangs at 100% CPU)
