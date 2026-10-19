# TGM765S-ET / TGM765L-ET 双课程硬件认识

依据官方资料制作的教学模型。双变体 7 英寸触摸屏的显示触控、供电、USB、串口、以太网、拨码与安装硬件认识；依据官方尺寸及外观图复建。

- [工业网络与组态技术](https://titleone01.github.io/tgm765-classroom/industrial-network/)
- [PLC应用技术](https://titleone01.github.io/tgm765-classroom/plc-application/)

运行 npm ci（已有 node_modules 可跳过）和 npm run build，同时生成两个独立课程目录和 offline 下两份真正的单文件 HTML。device.json 保存型号、版本、来源、主题、毫米坐标及有依据的可拆件；GLB使用米制，网页放大1000。每份离线HTML内嵌所有模型与脚本，单独改名后可断网打开。

静态部署：main 根目录，.nojekyll。sourceKind区分原厂CAD与教学复建，不混用型号或来源标签。模型压缩无损，原始完整GLB也保留在assets。

验收：Chrome/Edge、local/offline/online/iframe、信捷双版本、六面视图、标注投影、拆离/暂停/复位、320/390/768宽度。真实手机/触屏、实际教材平台、三家大陆运营商直连的状态以交付验收记录为准。
