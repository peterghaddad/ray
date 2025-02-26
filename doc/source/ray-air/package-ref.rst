.. _air-api-ref:

Ray AIR API
===========

.. contents::
    :local:

Components
----------

.. _air-preprocessor-ref:

Preprocessors
~~~~~~~~~~~~~

.. autoclass:: ray.data.preprocessor.Preprocessor
    :members:

.. automodule:: ray.data.preprocessors
    :members:
    :show-inheritance:

.. autofunction:: ray.air.train_test_split


.. _air-trainer-ref:

Trainers and Predictors
~~~~~~~~~~~~~~~~~~~~~~~

.. autoclass:: ray.train.trainer.BaseTrainer
    :members:

.. autoclass:: ray.train.predictor.Predictor
    :members:

.. autoclass:: ray.train.predictor.DataBatchType

.. autoclass:: ray.train.batch_predictor.BatchPredictor
    :members:

.. automodule:: ray.train.xgboost
    :members:
    :show-inheritance:

.. automodule:: ray.train.lightgbm
    :members:
    :show-inheritance:

.. automodule:: ray.train.tensorflow
    :members:
    :show-inheritance:

.. automodule:: ray.train.torch
    :members:
    :show-inheritance:

.. automodule:: ray.train.horovod
    :members:
    :show-inheritance:

.. automodule:: ray.train.huggingface
    :members:
    :show-inheritance:

.. automodule:: ray.train.sklearn
    :members:
    :show-inheritance:

.. autoclass:: ray.train.data_parallel_trainer.DataParallelTrainer
    :members:
    :show-inheritance:

.. autoclass:: ray.train.gbdt_trainer.GBDTTrainer
    :members:
    :show-inheritance:



.. _air-tuner-ref:

Tuner
~~~~~

.. autoclass:: ray.tune.tuner.Tuner
    :members:

.. automodule:: ray.tune.result_grid
    :members:

.. _air-serve-integration:

Serving
~~~~~~~

.. autoclass:: ray.serve.air_integrations.PredictorDeployment

.. autoclass:: ray.serve.air_integrations.PredictorWrapper

.. _air-results-ref:

Outputs
~~~~~~~

.. _air-checkpoint-ref:

Checkpoint
##########

.. automodule:: ray.air.checkpoint
    :members:

Result
######

.. automodule:: ray.air.result
    :members:


Configs
~~~~~~~

.. automodule:: ray.air.config
    :members:

.. autoclass:: ray.air.config.CheckpointConfig


.. _air-builtin-callbacks:

Callbacks
~~~~~~~~~

Comet
#####

.. autoclass:: ray.air.callbacks.comet.CometLoggerCallback

Keras
#####

.. autoclass:: ray.air.callbacks.keras.Callback
    :members:

MLflow
######

.. autoclass:: ray.air.callbacks.mlflow.MLflowLoggerCallback

Weights and Biases
##################

.. autoclass:: ray.air.callbacks.wandb.WandbLoggerCallback

.. _air-session-ref:

Session
~~~~~~~

.. automodule:: ray.air.session
    :members:
