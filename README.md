# Action Text for backblaze storage (using activestorage)

Action Text brings rich text content and editing to Rails. It includes the [Trix editor](https://trix-editor.org) that handles everything from formatting to links to quotes to lists to embedded images and galleries. The rich text content generated by the Trix editor is saved in its own RichText model that's associated with any existing Active Record model in the application. Any embedded images (or other attachments) are automatically stored using Active Storage and associated with the included RichText model.

You can read more about Action Text in the [Action Text Overview](https://edgeguides.rubyonrails.org/action_text_overview.html) guide.

## Usage

Add the following to your package.json

``` "@jeygeethan/actiontext-backblaze": "^6.1.3-alpha", ```

## License

Action Text is released under the [MIT License](https://opensource.org/licenses/MIT).
