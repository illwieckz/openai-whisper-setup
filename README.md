# Setup OpenAI's Whisper

Tool to install and run OpenAI's Whisper.

## How to

* Install (you need Python `virtualenv` to be installed first):  
  `./install`

* Use:  
  `./run <options> <file path>`

Example:

```sh
./run --language French --output_format vtt recording.flac
```

* Open a shell to do custom operations in the Python `virtualenv`:  
  `./shell`

Then you can do special commands, for example install [different versions of PyTorch](https://pytorch.org/get-started/locally/), for example:

```
pip install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/rocm6.3
```
