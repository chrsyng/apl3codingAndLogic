net command

The Net utility includes a host of subcommands that help you interact
with the network software. For example, you can use the Net utility to
add, view, edit, and delete users. To obtain a complete list of Net subcom-
mands, type Net /? and press Enter. To obtain help on using a specific Net
subcommand, use the Net Subcommand /? command, where Subcommand is
the subcommand that you want to use. For example, to learn more about
the Accounts subcommand, you’d type Net Accounts /? and press Enter.

## Syntax

```
net [accounts | computer | config | continue | file | group | help | helpmsg | localgroup | name | pause | print | send | session | share | start | statistics | stop | time | use | user | view]
```

## Examples

net view is one  of the simplest net commands that lists all the networked devices.

```
net view
```

Executing the net start command without any options following it is useful if you want to see a list of currently running services. This list can be helpful when managing services because you don't have to leave the command line to see which services are running.

```
net start
```

To stop the Print Spooler service from the command line. Services can also started, stopped, and restarted via the Services graphical tool in Windows (services.msc), but using the net stop command lets you control them from places like Command Prompt and batch files.

```
net stop "print spooler"
```
