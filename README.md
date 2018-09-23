# OmniAuth Tink

This is the official OmniAuth strategy for authenticating to ING. To
use it, you'll need to sign up for an OAuth2 Application ID and Secret
on the [ING Applications Page](https://developer.ing.com).

## Basic Usage

```ruby
use OmniAuth::Builder do
  provider :ing, ENV['ING_KEY'], ENV['ING_SECRET']
end
```
