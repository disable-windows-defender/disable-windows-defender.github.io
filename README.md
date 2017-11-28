# Disable Windows Defender on Windows 10

**Windows Defender is infamous for its tendency to monopolize CPU and I/O
resources.** Moreover, some of its "security" measures are undesirable and may
put user privacy at risk. This has many practical consequences, such as:

- slower general operation due to increased resource usage,
- excessive CPU usage while copying files, slowing down the entire system,
- increased heat and noise output, as well as reduced battery life on laptops,
- deletion of files detected as "malware" without the user's consent, even in
  ZIP archives or on attached network drives,
- user privacy at risk, due to automatic sending of "malware samples" to
  Microsoft,
- …

## Frequently asked questions

### Isn't it insecure to disable Windows Defender?

With today's security threats, antivirus software is becoming
less relevant over the years. Many antiviruses are now fooled by malware
executables, and other forms of malware aren't detected by most antiviruses.
While perfect security doesn't exist, it still is a good idea to avoid exposing
yourself to modern threats such as ransomware.

To make your computing more secure, consider the following options:

- Block tracking and malware scripts using
  [uBlock Origin](https://github.com/gorhill/uBlock).
  This will also make browsing faster and decrease network traffic.
- Block tracking and malware domains using
  [Dan Pollock's `hosts` file](http://someonewhocares.org/hosts/zero/).
  This has the upside of working on all software on your computer,
  not just Web browsers.

## License

Copyright © 2017 Hugo Locurcio and contributors

Files in this repository are licensed under CC0 1.0 Universal,
see [LICENSE.md](LICENSE.md) for more information.
