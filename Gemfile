source "https://rubygems.org"

# Upper-bounded (not exact-pinned, no Gemfile.lock is checked in) so routine
# patch/minor releases still flow in, but an unexpected major-version bump
# can't silently change build behavior between runs. CI also caches the
# resolved bundle (see build-ipa.yml's bundler-cache) so the same versions
# are reused run-to-run until this file changes.
gem "fastlane", ">= 2.220", "< 3.0"
gem "cocoapods", ">= 1.15", "< 2.0"
