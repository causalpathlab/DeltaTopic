# DeltaTopic: Dynamically-Encoded Latent Transcriptomic pattern Analysis by Topic modeling

### Example code for training BALSAM and DeltaTopic models

```python
# train BALASM model on the spliced count data
python BALSAM.py --nLV 32 --EPOCHS 5 
# train deltaTopic model
python DeltaTopic.py --nLV 32 --EPOCHS 5 
```

### Analysis Rmd code for reproduce figures in the paper

```bash
cd R_figures
make all
```
