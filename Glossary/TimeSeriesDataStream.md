---
title: TimeSeriesDataStream
keywords: 

status: Complete
created: 20210914
updated: 20211006
createdby: JennyWrenWolf
updatedby: JennyWrenWolf

Notes:  Example is from Data Stream - if this is based on time isn't it a better example here?  Each data point must have a time stamp.  Analysize based on the time stamps.  Time Bucket (a period of time where data is grouped for analysis)

---
[Home](../Index.md) > [Glossary](./Index.md)

# Time Series Data Stream
## Definition
An important feature of NuvIoT, is the ability to collect data and then use it to improve performance.  Time-Series Data Streams are an optimized storage technology that is very powerful for understanding the behavior of IoT [Devices](./Device.md) over a period of time. Every data point recorded in this type of [Data Stream](./DataStream.md) must have a time stamp. These data points may than be grouped together for analysis.  This sampling can be thought of as a *Time Bucket* which holds all the recorded data within a predefined period of time.  Operations may be performed on the *Time Bucket*, such as averaging, minimum and maximum values or standard deviations.  

For more in-depth information, click here: https://docs.microsoft.com/en-us/azure/architecture/data-guide/scenarios/time-series

<br>
<br>
<br>

## Example
Vibrations produced by a *Plymouth IoT Conveyor Belt* were recorded in a Time Series Data Stream.  [Machine Learning](./MachineLearning.md) analyzed the Time Series Data Stream to determine an acceptable level of vibration.  When the Time Series Data Streams began producing consistently higher levels of vibration, an [Error Code](./ErrorCode.md) was produced.
<br>
<br>
<br>

# Related Terms
- [Data Stream](./DataStream.md)
- [Devices](./Device.md)
- [Error Code](./ErrorCode.md)
- [Machine Learning](./MachineLearning.md)