此benchmarksql是开源版本benchmark5.0的改进版，在测试报告中新增了测量平均延迟的功能
==============================================================================

**原有的测试报告中只有90%尾延迟，如下图所示**
![854e28ae6e98e310ec84540ad9984b6](https://github.com/JiangYihe/benchmarksql5.0-nvmdb/assets/71739806/1ebb859d-af78-4ab5-8a7c-64936912abc2)

**对“run/mist/latency.R”和“run/generateReport.sh”进行了修改，增加了测量平均延迟的功能，并输出到表格，如下图所示**
![c54dadba5a52e996bdc911b4d349766](https://github.com/JiangYihe/benchmarksql5.0-nvmdb/assets/71739806/9b301a48-c700-4036-881f-6e2bf067f762)


**编译方法与开源版本的benchmarksql5.0相同**



