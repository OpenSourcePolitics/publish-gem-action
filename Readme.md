# Publish gem action

This action publish a Ruby gem.

## Inputs
- rubygems_api_key:
  - description: 'RubyGems API key'
  - required: true

## Example usage
```yaml
- name: Publish gem
  uses: OpenSourcePolitics/decidim-publish-gem-action@master
  with:
    rubygems_api_key: ${{ secrets.RUBYGEMS_API_KEY }}
```