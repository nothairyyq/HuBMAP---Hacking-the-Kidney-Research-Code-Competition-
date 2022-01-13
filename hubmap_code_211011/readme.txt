code中的代码按照
1hubmap-anatomy-zarr-test.ipynb
2hubmap-zarr-test.ipynb
3hubmap-efficient-sampling-ii-deepflash2-test1010.ipynb
4hubmap-deepflash2-train-test.ipynb
5hubmap-efficient-sampling-deepflash2-sub.ipynb。


代码之间存在的逻辑关系如下
3hubmap-efficient-sampling-ii-deepflash2-test1010.ipynb需要调用1hubmap-anatomy-zarr-test.ipynb中的结果

4hubmap-deepflash2-train-test.ipynb需要调用2hubmap-zarr-test.ipynb和3hubmap-efficient-sampling-ii-deepflash2-test1010.ipynb中的结果

5hubmap-efficient-sampling-deepflash2-sub.ipynb 需要调用5hubmap-efficient-sampling-deepflash2-sub.ipynb中的结果。