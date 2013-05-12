# <img src="https://raw.github.com/schmich/kappa/master/assets/kappa.png" /> Kappa

Kappa is a Ruby library for interfacing with the [Twitch.tv API](https://github.com/justintv/Twitch-API).

## Getting Started

`gem install kappa --pre`

```ruby
require 'kappa'

include Kappa::V2

grubby = Channel.get('followgrubby')
puts grubby.streaming?
```

## Examples

## Contributing

## License

Copyright &copy; 2013 Chris Schmich
<br />
MIT License, see LICENSE for details.
