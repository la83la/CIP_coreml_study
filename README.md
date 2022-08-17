`Use coremltools to convert machine learning models from third-party libraries to the Core ML format.😀`

# How to use
You can use trained models from frameworks like Caffe, Keras, and scikit-learn, among others, and using coremltools, a Python library provided by Apple, you can convert those models to the CoreML format.

```python
# Convert model to Core ML 
coreml_model = coremltools.converters.sklearn.convert(model, input_features=['alcohol','malicAcid', 'ash', 'alkalinityAsh', 'magnesium', 'totalPhenols'])

# Save Core ML Model
coreml_model.save('wine.mlmodel')
print('Core ML Model saved')

print('This tool is easy and fun to use!!!')
```
With coremltools, you can do the following:

Convert trained models to the Core ML format.
Read, write, and optimize Core ML models.
Verify conversion/creation (on macOS) by making predictions using Core ML.
After conversion, you can integrate the Core ML models with your app using Xcode.

# problems encountered
1. python version 
2. scikit-learn version
3. coremltools version
