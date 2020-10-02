# Code and Datasets for "Noise or Signal: The Role of Image Backgrounds in Object Detection"
Repository for "Noise or Signal: The Role of Image Backgrounds in Object Detection"

## Links to datasets
- Main release (test data, all datasets): [Download link (tar file)](https://anonymousiclr3011.s3.us-east-2.amazonaws.com/test_sets.tar.gz)
- Training datasets:
  - [ImageNet-9L](https://anonymousiclr3011.s3.us-east-2.amazonaws.com/in9l.tar.gz)
  - [Mixed-Next](https://anonymousiclr3011.s3.us-east-2.amazonaws.com/mixed_next.tar.gz)
  - [Mixed-Rand](https://anonymousiclr3011.s3.us-east-2.amazonaws.com/mixed_rand.tar.gz)
  - [Mixed-Same](https://anonymousiclr3011.s3.us-east-2.amazonaws.com/mixed_same.tar.gz)
  - [No-FG](https://anonymousiclr3011.s3.us-east-2.amazonaws.com/no_fg.tar.gz)
  - [Only-BG-B](https://anonymousiclr3011.s3.us-east-2.amazonaws.com/only_bg_b.tar.gz)
  - [Only-BG-T](https://anonymousiclr3011.s3.us-east-2.amazonaws.com/only_bg_t.tar.gz)
  - [Only-FG](https://anonymousiclr3011.s3.us-east-2.amazonaws.com/only_fg.tar.gz)
  - [Original](https://anonymousiclr3011.s3.us-east-2.amazonaws.com/original.tar.gz)

To evaluate a model:

```bash
python eval.py --eval-dataset 'original' --data-path '/PATH/TO/DATA' --arch mobilenetv3_large_100
```

See [here](https://rwightman.github.io/pytorch-image-models/results/) for a list of supported architectures.
