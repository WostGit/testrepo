# Qwopus3.5 9B 4-bit MLX memory test

Status: `passed`
Model: `Jackrong/MLX-Qwopus3.5-9B-v3-4bit`
Model URL: <https://huggingface.co/Jackrong/MLX-Qwopus3.5-9B-v3-4bit>
Started: `2026-05-26T10:35:56Z`
Updated: `2026-05-26T10:37:20Z`
Runner: `GitHub Actions 1000004755 macOS ARM64`
Platform: `macOS-26.4-arm64-arm-64bit`
GitHub SHA: `00e6d60773a16e31ecefe17b8d6f32e501eb245a`
Peak process RSS GiB: `1.6745` at `background_monitor`
Min system available GiB: `0.6789` at `background_monitor`
Memory sample count: `30`

## Hugging Face metadata
Model ID: `Jackrong/MLX-Qwopus3.5-9B-v3-4bit`
Revision SHA: `7f75eaf78e0da7e23ef84471aaa7331f0d8de6e2`
Tags: `['mlx', 'safetensors', 'qwen3_5', 'unsloth', 'qwen', 'qwen3.5', 'reasoning', 'chain-of-thought', 'lora', 'competitive-programming', 'text-generation', 'conversational', 'en', 'zh', 'ko', 'base_model:Jackrong/Qwopus3.5-9B-v3', 'base_model:adapter:Jackrong/Qwopus3.5-9B-v3', 'license:apache-2.0', '4-bit', 'region:us']`
Approx selected file bytes: `5058234647`

## MLX load
Load seconds: `41.9549`
Device before load: `Device(gpu, 0)`
Device after load: `Device(gpu, 0)`

## Generation tests
| Test | OK | Max tokens | Seconds | Requested tok/s | Output tokens |
|---|---:|---:|---:|---:|---:|
| one_token_smoke | True | 1 | 31.4673 | 0.0318 | 1 |
| two_token_smoke | True | 2 | 3.2225 | 0.6206 | 2 |
| eight_token_smoke | True | 8 | 4.967 | 1.6106 | 8 |

### one_token_smoke output
```text
I
```

### two_token_smoke output
```text
, so
```

### eight_token_smoke output
```text


<think>
The user wants me to
```

## Memory artifacts

- `qwopus35-9b-4bit-mlx-memory.log`
- `qwopus35-9b-4bit-mlx-memory-samples.jsonl`
- `qwopus35-9b-4bit-mlx-memory-results.json`
