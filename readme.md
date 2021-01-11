# 新冠疫情可视化地图

## 步骤

1. 搭建环境

    ```shell
    python3 -m venv gis_env
    source ./gis_env/bin/activate
    pip3 install -r requirements.txt
    ```

2. 获取数据

    ```shell
    git clone https://github.com/CSSEGISandData/COVID-19.git
    ```

    > 更新数据
    >
    > ```shell
    > cd COVID-19
    > git pull https://github.com/CSSEGISandData/COVID-19.git
    > ```
    >
3. 生成地图

    ```shell
    source ./gis_env/bin/activate
    python3 ./src/main.py
    ```

4. 查看地图
   使用任意浏览器打开`COVID-map.html` 