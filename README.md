# ![LOGO](logo.png) Custom Vision Prediction Client **flow**ground Connector

## Description

A generated **flow**ground connector for the Custom Vision Prediction Client API (version 2.0).

Generated from: https://api.apis.guru/v2/specs/microsoft.com/cognitiveservices-Prediction/2.0/swagger.json<br/>
Generated at: 2019-05-07T17:43:02+03:00

## API Description



## Authorization

This API does not require authorization.

## Actions

### Predict an image and saves the result

*Tags:* `ImagePredictionApi`

#### Input Parameters
* `projectId` - _required_ - The project id
* `iterationId` - _optional_ - Optional. Specifies the id of a particular iteration to evaluate against.
            The default iteration for the project will be used when not specified
* `application` - _optional_ - Optional. Specifies the name of application using the endpoint
* `Prediction-Key` - _required_

### Predict an image without saving the result

*Tags:* `ImagePredictionApi`

#### Input Parameters
* `projectId` - _required_ - The project id
* `iterationId` - _optional_ - Optional. Specifies the id of a particular iteration to evaluate against.
            The default iteration for the project will be used when not specified
* `application` - _optional_ - Optional. Specifies the name of application using the endpoint
* `Prediction-Key` - _required_

### Predict an image url and saves the result

*Tags:* `ImagePredictionApi`

#### Input Parameters
* `projectId` - _required_ - The project id
* `iterationId` - _optional_ - Optional. Specifies the id of a particular iteration to evaluate against.
            The default iteration for the project will be used when not specified
* `application` - _optional_ - Optional. Specifies the name of application using the endpoint
* `Prediction-Key` - _required_

### Predict an image url without saving the result

*Tags:* `ImagePredictionApi`

#### Input Parameters
* `projectId` - _required_ - The project id
* `iterationId` - _optional_ - Optional. Specifies the id of a particular iteration to evaluate against.
            The default iteration for the project will be used when not specified
* `application` - _optional_ - Optional. Specifies the name of application using the endpoint
* `Prediction-Key` - _required_

## License

**flow**ground :- Telekom iPaaS / microsoft-com-cognitiveservices-prediction-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
