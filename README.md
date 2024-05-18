## Usage

- [original repo](https://github.com/wvsharber/BeatMapSynthesizer)

```console
python -m venv venv

venv/Script/activate

pip install -r ./requirement.txt

python beatmapsynth.py ['filepath'] ['Song Name'] [difficulty] [model] [optional: -k] [optional: --version]
```

## Changes

- Add requirement.txt
- Fix bpm demension error.
- Generate zip in the same directory as the original file.
- Add difficulty 'all'
- Change file name Easy.dat to EasyStandard.dat ...
- Change map version 3.0.0 from 2.0.0