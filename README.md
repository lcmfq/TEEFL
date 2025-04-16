项目名称：{基于机密计算的联邦学习框架}   
项目链接：{https://github.com/lcmfq/TEEFL/edit/main/README.md}  
导师信息：{麻付强，mafuqiang@ieisystem.com，浪潮信息、龙蜥社区}  
难度：{中}   
分类：{安全应用}  
题目要求：{在满足数据隐私、安全和监管要求的前提下，联邦学习让机器学习参与方能够更加高效、准确的共同使用各自的数据进行模型训练。但是目前联邦学习的参数聚合过程一般采用同态加密、多方安全计算等技术进行防护，其整体通信成本高，训练效率低，因此需要对参数安全聚合过程进行改进。而机密计算技术基于硬件可信执行环境不仅可以保证联邦学习参数聚合过程的安全，同时性能损失较低。因此，需要设计一种基于机密计算的联邦学习的聚合框架。}    
特征：{1、基于FATE、FederatedScope等开源联邦学习框架，聚合服务器运行在机密计算环境中，保证参数聚合安全；  
2、至少支持两种机密环境，例如Intel SGX、Intel TDX、海光CSV；  
3、支持远程证明功能，各个参与方能够对参数聚合服务器的环境真实性进行验证；  
4、参与方与参数聚合服务器能够基于远程证明建立安全信道，并传输模型参数；  
5、（加分项）各个参与方的训练过程也运行在可信执行环境中；  
6、（加分项）基于龙蜥社区的CAI方案，支持CPU+GPU的异构机密计算环境}  
预期目标{完成基础功能和扩展功能的开发，提交相应代码，并输出设计、测试类文档。}  
License：{Apache 2.0 }  
参考资料：{
[1] 龙蜥社区机密计算SIG：https://openanolis.cn/sig/coco  
[2] rats-tls开源项目：https://github.com/inclavare-containers/rats-tls  
[3] FederatedScope开源项目：https://federatedscope.io/   
[4]远程证明组件：https://github.com/openanolis/trustee}  
备注：{ }
