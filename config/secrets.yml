# Be sure to restart your server when you modify this file.

# Your secret key is used for verifying the integrity of signed cookies.
# If you change this key, all old signed cookies will become invalid!

# Make sure the secret is at least 30 characters and all random,
# no regular words or you'll be exposed to dictionary attacks.
# You can use `rails secret` to generate a secure secret key.

# Make sure the secrets in this file are kept private
# if you're sharing your code publicly.

# Shared secrets are available across all environments.

# shared:
#   api_key: a1B2c3D4e5F6

# Environmental secrets are only available for that specific environment.

development:
  secret_key_base: 6498e1f0affa6721f4db0a8760999533464df6b0de302bafd99a4adb7eaa6b101581073d75d347b158b4196e885b8b83c4c7bdf96bba8f43b2e088bbe14c619f

test:
  secret_key_base: 4e7decd9827793ae7c28b9bb91da3af21549856b0c780b8773a9d0817284f2e889e0632337a4bd8d28bc532fab76575a5d476d7c6143e26e9399ad7921e182ed

# Do not keep production secrets in the unencrypted secrets file.
# Instead, either read values from the environment.
# Or, use `bin/rails secrets:setup` to configure encrypted secrets
# and move the `production:` environment over there.

production:
  secret_key_base: <%= ENV["SECRET_KEY_BASE"] %>
