# open webui functions

A collection of various functions for [Open WebUI](https://github.com/open-webui/open-webui), an open source LLM frontend.

You can read the documentation for Open WebUI functions here: <https://docs.openwebui.com/features/plugin/functions/>

## Anthropic Manifold Pipe `anthropic_manifold_pipe.py`

This [Pipe Function](https://docs.openwebui.com/features/plugin/functions/) adds support for Anthropic models.

Features:

- Enables an (opinionated) subset of recent Anthropic models
- Supports thinking
- Thinking can be configured per model, conversation, or globally using the usual `Reasoning Effort` setting in the UI. The supported values are: `none`, `low`, `medium`, `high`, `max`
- Configure the Anthropic API key in the UI as a [valve](https://docs.openwebui.com/features/plugin/valves/)

**Credits:** the implementation borrows heavily from several other functions for adding Anthropic models:

- <https://github.com/open-webui/pipelines/blob/main/examples/pipelines/providers/anthropic_manifold_pipeline.py>
- <https://openwebui.com/f/markkazakov/anthropic> (`./old_anthropic_manifold_pipe.py`)
