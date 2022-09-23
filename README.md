# Assignment

Add "per step logging" (training step), and log "hp_metric" in tensorboard as validation loss
(https://pytorch-lightning.readthedocs.io/en/stable/api/pytorch_lightning.loggers.tensorboard.html#pytorch_lightning.loggers.tensorboard.TensorBoardLogger.log_hyperparams (Links to an external site.))

Do a Hyperparam sweep for CIFAR10 dataset with resnet18 from timm.

Find the best batch_size and learning rate, and optimizer

Optimizers have to be one of Adam, SGD, RMSProp

1) you can use colab for this(docker is not necessary for this). and train on TPUs/GPUs, either is fine. (CPU training will be really SLOW !)

2) Push model, logs and data to google drive (using dvc) make the folder public and share link of the google drive folder (must be public)
Push the pytorch lightning - hydra template with the dvc changes that we made to github
share link to the github repo

3) Upload Tensorboard logs to (https://tensorboard.dev/) and share link to the tensorboard.dev 
(https://colab.research.google.com/github/tensorflow/tensorboard/blob/master/docs/tbdev_getting_started.ipynb#scrollTo=n2PvxhOkW7vn (Links to an external site.))
 
