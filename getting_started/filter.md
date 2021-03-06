# Filter

In production environments we want to have full control of the data we are collecting, filtering is an important feature that allows to **alter** the data before to deliver it to some destination.

![](../.gitbook/assets/logging_pipeline_filter%20%281%29.png)

Filtering is implemented through plugins, so each filter available could be used to match, exclude or enrich your logs with some specific metadata.

Very similar to the input plugins, Filters runs in an instance context, which it have it own and independent configuration. Configuration keys are often called **properties**.

For more details about the Filters available and it usage, please refer to the [Filters](../filter/) section.

