## Local AI
This container bundles Local AI and auto-configures it for you. It support hardware acceleration with Vulkan.

### Notes
Documentation is available on the container repository. This documentation is regularly updated and is intended to be as simple and detailed as possible. Thanks for all your feedback!

- See https://github.com/docjyJ/aio-local-ai-vulkan#getting-started for getting start with this container.
- See [this guide](https://github.com/nextcloud/all-in-one/discussions/5430) for how to improve AI task pickup speed
- Note that Nextcloud supports only one server for AI queries, so this container cannot be used at the same time as other AI containers.
- If the Assistant web UI shows an empty answer, verify that the configured service URL ends with `/v1` (for this container: `http://nextcloud-aio-local-ai:10078/v1`), download at least one text model in LocalAI, and select it as the default completion model in the Nextcloud AI admin settings.
- See https://github.com/nextcloud/all-in-one/tree/main/community-containers#community-containers how to add it to the AIO stack

### Repository
https://github.com/docjyJ/aio-local-ai-vulkan

### Maintainer
https://github.com/docjyJ
