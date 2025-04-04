# Kubeflow Components

## KSERVE Available Frameworks  

The following machine learning frameworks are supported in KSERVE:  

```python
AVAILABLE_FRAMEWORKS = {
    'tensorflow': V1beta1TFServingSpec,
    'pytorch': V1beta1TorchServeSpec,
    'sklearn': V1beta1SKLearnSpec,
    'xgboost': V1beta1XGBoostSpec,
    'onnx': V1beta1ONNXRuntimeSpec,
    'triton': V1beta1TritonSpec,
    'pmml': V1beta1PMMLSpec,
    'lightgbm': V1beta1LightGBMSpec
}
