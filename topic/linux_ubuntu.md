# Linux / Ubuntu

## Admin

```bash
# Clear Syslog
> /var/log/syslog
```

```bash
# Restart Syslog Service
systemctl restart syslog # Option 1
service syslog restart # Option 2
```

[Using Log Rotate for Syslog, etc](https://stackoverflow.com/questions/35638219/ubuntu-large-syslog-and-kern-log-files?utm_source=pocket_mylist)

## Command Line

`CTRL` + `C` - Stop running command.  
`CTRL` + `D` - Close current shell session.  
`CTRL` + `L` - Clear screen. (Scrolls you down in reality)

`CTRL` + `A` - Go to beginning of line.  
`CTRL` + `E` - Go to end of line.  
`CTRL` + `F` or `Right` - Next word.  
`CTRL` + `B` or `Left`- Previous word.

`ALT` + `Backspace` - Delete last word.  
`CTRL` + `U` - Delete whole line.

### Autocomplete

Single `TAB`- Autocompletes if only 1 file meets wildcard condition
Double `TAB`- Lists all files meeting wildcard condition

### History

```bash
history # List command history

history | grep command-name     # Search history for a particular command string
```
`CTRL` + `R` - Search command history. Hit again for previous command.
`CTRL` + `G` - Preserves the command selected and gets out of search mode
