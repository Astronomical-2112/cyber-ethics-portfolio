## Policy Snippet

###### The AI detection system has been authorized for use on the organization's network.  The terms of use will be amended to let users know that their traffic is being monitored by an AI tool, and may be used in the future for further training.  The AI can only detect unusual network traffic.  It is not authorized to act without any human involvement.  It can only alert members of the security team to act when anything out of the ordinary occurs.  Once the security team is alerted, they can monitor the issue, in the event of a false flag the data will be anonymized, and stored securely for future use in the models training.  Data on the model's precision (TPR) and the recall (FPR) will be tracked.  Retraining will occur based on the TPR and FPR.

## Controls & Metrics

#### Drift monitoring

###### The model will be retrained if the recall value is greater than 0.3 pp/quarter

#### Fairness

###### If a subgroup FPR value ends up being greater than 0.3 pp, the model is retrained

## Justification

###### The values used measure the ability to check for threats.  Measuring its ability to check for the existance of a threat.  The primary risk we are checking for is obvious, if the model can't find any issues, it is going to be a problem for it to do anything at all.  
