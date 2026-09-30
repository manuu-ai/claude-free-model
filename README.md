// how to connect the claude to bypass there models to use you models.

this is "setting.json" or "setting.local.json" file add the below env add both file. 

1. main is inside the .claude folder settings.local.json, here add the env variable inside api key should created
2. file name is .claude.json here you need to add the variable "hasCompletedOnboarding": true
3. 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
4. after that go to .claude folder addd the env variable to settings.json



This is the env variable.
{
  "env": {
    "ANTHROPIC_BASE_URL": "https://openrouter.ai/api",
    "ANTHROPIC_AUTH_TOKEN": "",
    "ANTHROPIC_API_KEY": "",
    "ANTHROPIC_MODEL": "nvidia/nemotron-3-super-120b-a12b:free",
    "ANTHROPIC_DEFAULT_OPUS_MODEL": "nvidia/nemotron-3-super-120b-a12b:free",
    "ANTHROPIC_DEFAULT_SONNET_MODEL": "nvidia/nemotron-3-super-120b-a12b:free",
    "ANTHROPIC_DEFAULT_HAIKU_MODEL": "thinkingmachines/inkling:free",
    "ANTHROPIC_DEFAULT_FABLE_MODEL": "openrouter/free",
    "CLAUDE_CODE_SUBAGENT_MODEL": "openrouter/free",
    "CLAUDE_CODE_MAX_CONTEXT_TOKENS": "256000"
  }
}

