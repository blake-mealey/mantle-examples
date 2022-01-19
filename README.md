# Mantle Examples

This repo contains example projects for learning [Mantle](https://mantle-docs.vercel.app).

## Usage

```sh
# 1. Clone the repo
git clone https://github.com/blake-mealey/mantle-examples
cd mantle-examples

# 2. Install Mantle with Foreman - for more information, see
#    https://mantle-docs.vercel.app/docs/Installation
foreman install

# 3. Deploy an example project. All examples configure at least
#    two environments, `dev` and `prod`
mantle deploy examples/getting-started --environment dev

# 4. If you're done with an example, you can destroy it
mantle destroy examples/getting-started --environment dev
```

> Note that if you are not using Windows (or you are not logged in on Roblox Studio on your computer),
> you will need to set your `ROBLOSECURITY` environment variable. See the
> [Authentication](https://mantle-docs.vercel.app/docs/Authentication) guide for more details.

To get a good understanding of Mantle, you are encouraged to play around with the example projects
and see how things change when you re-run `mantle deploy`. Check out the
[Configuration](https://mantle-docs.vercel.app/docs/Configuration) guide for the full list of
options.
