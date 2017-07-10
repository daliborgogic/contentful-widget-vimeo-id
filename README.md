Vimeo ID
--------------

![vimeo-id](https://github.com/daliborgogic/contentful-widget-vimeo-id/assets/youtube-id.png)

This extension extracts the video ID from a Vimeo URI.

### Installation and usage

Compile the extension:

```bash
npm i
make
```

Install extension for space:

```bash
export CONTENTFUL_MANAGEMENT_ACCESS_TOKEN=<your Contentful management api token>
export SPACE=<id of space you want to install extension for>

contentful-extension create --space-id $SPACE
```

From this point on, you can use the [other commands](https://github.com/contentful/contentful-extension-cli#available-commands) the contentful-extension-cli provides.
 
