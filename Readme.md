# Conspectus helper

### This small script on python for automatic process of creating electronic conspectus

Accept docx and pdf files for reproduce and all result put in ./result

## Install

Install python dependencies

```bash
pip install -r requirements.txt
```

10150.ttf its font - Eskal Font4You (Enough truthful and beautiful font, looks like a letter from hand)

```
mv 10150.ttf ~/.local/share/fonts/ && fc-cache
```

## Use

```bash
./conspus sources
```

## Quickly use

```bash
mv conspus ~/.local/bin/
```

## Plan

- Add option for auto margin to printing on sheets

### Small history

In this quarantine, my teachers thought that for two days to write a summary of 15 sheets A4 is normal, I decided that it was not honest and wrote this little script
