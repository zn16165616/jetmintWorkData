- Agent
  - 用户
    - 1.注册用户
      - 1.手机或邮箱
      - 2.验证码
      - 3.登陆密码
      - 提示
        - 谷歌绑定
        - 邮箱绑定
    - 2.安全
      - 1.手机
      - 2.邮箱
      - 3.谷歌验证
        - 更换需要7天
    - 3.用户冻结
      - 客服可以冻结用户，冻结用户无法登陆系统
    - 4.登陆与注册
      - 平台各功能页面如监测用户未登陆，则不需跳转至登陆，而在用户当前页面弹出登陆以及注册页面，待完成登陆或注册后直接进入当前页面，不进行跳转。
  - 资产发行
    - 门槛
      - 已注册用户
    - 发行
      - 1.给出资产名称和总量
        - 1.资产名称（选填）
        - 2.资产代码（必填）
        - 3.发行总量（必填）
        - 4.logo（选填）
          - 用户本地上传，系统自动上传至oss系统，生成图床链接
        - 5.描述（选填）
        - 6,联邦地址（选填）
          - 只接受已部署stellar服务的联邦地址
      - 2.扣除1%
      - 3.资产创建
        - 1.如果联邦地址已填写，挂到联邦地址上，不填默认挂到jetmint.org
        - 2.资产code唯一
  - 发起募集活动
    - 活动门槛
      - 1.已注册用户
      - 2.持有已登记资产的代币
    - 发起募集活动
      - 1.登记信息
        - 1.活动名称
        - 2.选择资产（Token symbol）
        - 3.接受募集币种（Accept Token symbol）
          - 恒星（默认选择）
          - 以太坊
        - 4.总配给额（Total supply of token）
        - 5.兑换比例（Conversion Rate）
          - 恒星兑换比例
          - 以太坊兑换比例
        - 6.总募集额（Total allotment）
          - 根据总配给额以及兑换比例自动计算恒星总量及以太坊总量
          - 显示以或的形式显示
        - 7.上传材料（仅限pdf）
        - 8.起止时间（start time - end time）
        - 9.最小参投额（Minimum Contribution）
        - 10.最大参投额（Maximum Contribution）
        - 11.锁定周期（Lock-up period）
        - 12.展示图片
      - 2.锁定相应数量代币
      - 3.扣除手续费
      - 4.可查看活动信息以及代币对应的项目信息
        - 1.活动创建后默认为私密状态，非发起方许可（白名单）用户无法显示
          - 活动创建后，发起方可以分享至QQ、微信
          - 收到分享用户可点击直接进入到该活动详情中
          - 登陆后自动加入活动发起方的白名单中
        - 2.发起方可以设置公开，公开后需审核
        - 3.活动状态
          - 1.即将开始、comming
          - 2.进行中、inprogress
          - 3.结束、done
        - 4.活动发起方可以删除白名单
    - 参与募集活动
      - 1.充值
      - 2.参投，获得锁定的相应代币数量
    - 发币/退回
      - 1.活动取消
        - 发起方需联系客服进行活动取消
        - 取消后参投用户参投单撤回，参投资产撤回
      - 2.活动发币
        - 活动结束后发起方可进行发币操作
        - 发币后，进行结算
          - 项目方锁定代币结算后解除锁定
          - 参投方锁定代币解除锁定
    - 生命周期
      - 募集活动即将开始以及进行中
        - 通过设定的活动开始时间进行判断
      - 募集活动结束
        - 已全额募集完毕
        - 超过募集的截止时间
  - 资产发行记录
    - 1.logo
    - 2.资产名称
    - 3.资产代码
    - 4.联邦地址
    - 5.发行账户
    - 6.发行时间
  - 募集发起记录
    - 1.活动名称
    - 2.接受募集币种（Accept Token symbol）
      - 恒星（默认选择）
      - 以太坊
    - 3.进度
    - 4.倒计时
    - 5.展示图片
    - 6.状态
  - 募集参投记录
    - 活动名
      - 可以点击查看活动信息
    - 资产种类
    - 参投数量
    - 兑换比例
    - 可兑换数量
    - 参投时间
    - 状态
      - 进行中
      - 己发币
  - 资产与募集活动详情
    - 资产信息
      - logo
      - 资产名称
      - 资产代码
      - 发行总量
      - 流通数量
      - 锁仓数量
      - 资产描述
      - 官方网址
      - 白皮书
        - pdf在线预览
      - 社区信息
        - qq
        - 微信
        - 电报
    - 活动信息
      - 活动类型
        - 募集
      - 登陆用户
        - 募集信息
          - 1.活动名称
          - 2.选择资产（Token symbol）
          - 3.接受募集币种（Accept Token symbol）
            - 恒星（默认选择）
            - 以太坊
          - 4.总配给额（Total supply of token）
          - 5.兑换比例（Conversion Rate）
            - 恒星兑换比例
            - 以太坊兑换比例
          - 6.总募集额（Total allotment）
            - 根据总配给额以及兑换比例自动计算恒星总量及以太坊总量
            - 显示以或的形式显示
          - 7.上传材料（仅限pdf）
          - 8.起止时间（start time - end time）
          - 9.最小参投额（Minimum Contribution）
          - 10.最大参投额（Maximum Contribution）
          - 11.锁定周期（Lock-up period）
  - 资产管理
    - 显示
      - 平台默认显示XLM、ETH、XYZ三种代币
      - 用户发行资产后自动添加该资产，仅显示给该发行资产用户
      - 用户参投发币后自动添加该资产，仅显示给该参投资产用户
      - 可以添加资产
        - 动态搜索stellar资产
        - 输入资产代码，搜索资产信息
          - 资产代码（code）
          - 资产描述（desc）
          - 发行账户（issue_account）
          - 联邦地址
          - logo
    - 提币
      - 选择提币地址
        - 地址添加
        - 在当前页面弹出页面进行填加或修改
          - 地址信息
            - 地址
            - 备注
            - 标签
          - 验证
            - 默认登陆的手机或邮箱验证
            - 谷歌验证
              - 如谷歌未绑定，则在当前页面弹出进行绑定，绑定后自动关闭并显示当前页面
      - 输入提币数量
        - 提示最多提币量
      - 验证
        - 默认登陆的手机或邮箱验证
        - 谷歌验证
          - 如谷歌未绑定，则在当前页面弹出进行绑定，绑定后自动关闭并显示当前页面
      - 确认提币
        - 需后台客服处理后显示提币成功
    - 充币
      - 显示充值地址，二维码
      - 备注
        - 用户充币
        - 平台分红
        - 募集发币
    - 记录显示
      - 充币记录
        - 充值
        - 募集发币
        - 平台分红
      - 提币记录
  - 挖矿活动
    - 玩法与规则
    - 昨日挖矿获得xyz
    - 昨日收益分配
      - xyz
      - xlm
      - 每持有100xyz可分配多少xyz，多少xlm
    - 今日收益分配
      - xyz
      - xlm
- boss
  - 工作台
    - leader
      - 大额提币消息（电话通知）
        - 操作
          - 生成系统xdr
          - 拷贝xdr至独立签名工具执行签名
          - 签名后拷贝至boss进行执行
    - custom service
      - 小额提币消息（电话通知）
        - 触发机制
          - 用户同一天对同一个资产提交三次（包括三次）及以上
          - 同一资产提币间隔时间小于5分钟
        - 操作
          - 生成系统xdr
          - 拷贝xdr至独立签名工具执行签名
          - 签名后拷贝至boss进行执行
      - 用户变更消息
        - 触发机制
          - 只能提供一种方式进行解锁
        - 点击消息直接进入用户详情，在变更请求中重置
  - 信息核查
    - 按用户（用户id/地址）
      - 通过用户id、手机号、邮箱查询
      - 显示用户注册时间，用户memo、、用户余额，冻结余额
        - 绑定信息（是否绑定手机、邮箱、谷歌）
        - 用户账务情况
          - 用户资产、进账统计、出账统计
            - 可按周、月、季统计
            - 点击资产查看资产明细
            - 点击进账，查看充值明细
              - 用户充值
              - 募集发币
              - 分红充值
              - 资产发行
            - 点击出账，查看提币明细
              - 最近用户提币信息，可点击查看更多（大额信息进行区分）
        - 最近登陆时间与ip，最近充值数量与时间、最近提币时间与数量
        - 最近用户资产发行信息，可点击查看详情
        - 异常行为日志
          - 登陆异常
          - 提币异常
            - 当天连续提币3笔及以上
            - 大额提币
          - 连续修改登陆密码
        - 变更请求
          - 变更内容
          - 变更时间
          - 处理时间
          - 客服解锁，用户变更保存
    - 按资产
      - 根据资产code、发行账户查询
      - 查看资产详情
        - 总量（Total Supply）
        - 持有者数量（Holders）
        - 交易单数量（Transfers）
        - 发行账户
        - 发行用户id
        - 资产编码+logo
        - 描述
        - 详细信息
          - 交易单（Transfers）详情（融入平台的交易单）
            - hash
            - age
            - from
            - to 
            - quantity
          - 持有者（融入平台持有者）
            - rank
            - address
            - memo
            - quantity
            - percentage
          - 白皮书
          - 联系信息
          - 活动（已公开）
            - 点击查看活动详情
    - 按活动
      - 募集活动
        - 根据募集活动名称或募集资产查询
        - 详细信息
          - 募集活动名称
          - 募集配额
          - 募集币种
          - 筹集信息
          - 筹集结果
          - 开始时间
          - 结束时间
          - 锁定天数
          - 活动文档
        - 活动公开审核
    - 信息查询
      - 普通查询
        - 选择表实体，选择查询条件，输入查询值（可添加多个条件），查询并显示查询结果
      - 选择查询模版
        - 根据模版输入查询条件
        - 展现查询结果
  - 收益分红
    - 添加挖矿活动
      - 1.设置本次活动xyz总量
      - 2.设置快照时间
      - 3.启动、停止
      - 分红计算
        - 1.根据快照时间进行快照
          - 1.xyz持有快照
          - 2.手续费快照（手续费总额*0.8）
        - 2.根据分红快照时间发放分红
          - 1.平台上的用户资产直接分红至用户上
          - 2.平台外xyz持有者，需登陆平台后，输入g串领取
            - 领取后直接分红至g串账户上
        - 3.根据挖矿返还xyz时间发放xyz
          - 1.客服设置xyz、xlm价值
          - 2.计算xyz返还用户
    - 收益分红计算（后台）
      - 根据快照时间，发出快照命令，获取快照数据
      - 根据快照时间，获取手续费
      - 设置xyz、xlm价格
      - 收益分红
        - 根据快照地址进行全网分红计算
          - 场外单（扣除平台地址外，其他的分红单）
          - 场内单
            - 核实快照数量是否与平台所有的余额总和一致
            - 根据平台所有用户持有持有xyz情况生成场内单
        - 分红
          - 场内单直接对其用户进行充值，备注，收益分红
          - 场外单，用户需登陆平台输入地址进行分红提取
            - 直接对地址进行验证，分红直接支付给该地址
            - 用户对应生成充值记录和提币记录
      - 挖矿返还
        - 根据快照时间，获取手续费
        - 设置xyz、xlm价格
        - 根据手续费单，计算挖矿返还单
        - 扣除已挖出数量
    - 收益分红单
      - 客服点击执行
    - 挖矿返还单
      - 客服点击执行
  - 平台账户划账
    - 系统账户、客服账户、董事账户划账
      - 点击后，核算账户所有的资产，按照系统账户、客服账户、董事账户7:2:1比例进行核算，生成划账单。
      - 相应推送客服、董事进行签名确认划转
    - 大单支付
      - 超过70%资产提币，参见支付场景
- boss-stellar
  - 五个资产账户
    - 1.系统账户、负责用户小额（当前用户额度比例）提币，系统签名支付
      - 达成条件
        - 1.用户提币额度占余额30%以下（与）
        - 2.用户当天提币三次以下（或）
        - 3.用户两笔提币间隔小于5分钟（或）
      - 签名
        - 系统签名
    - 2.客服账户、负责用户小额提币，需客服确认
      - 达成条件
        - 1.用户提币额度占余额30%以下（与）
        - 2.用户当天提币三次（包含三次）以上时（或）
        - 3.距前一笔提币时间间隔小于5分钟时（或）
      - 签名
        - 客服签名、系统签名
    - 3.董事账户、负责用户大额提币
      - 达成条件
        - 1.用户提币额度占余额30%以上（包括30%）
      - 签名
        - 1+N董事签名、系统签名
    - 4.1%代币手续费账户，负责收取资产发行1%代币
      - 提币条件                            
        - 2+N董事签名、系统签名
    - 5.平台外分红账户
  - 双向安全认证
    - 做任何一个operation时，都需要进行消息源的认证确认
  - 资产发行
    - boss触发，主动调用
    - 发送资产code、总量-> 资产发行 -> 返回G串 ZZZ
  - 充值记录
    - stellar触发，主动调用
    - 监控链上所有资产充值记录，记录发给boss
  - 签名工具
    - 大额提币时，消息主动推给leader（老刘），做第一人签名，线下交给第二人进行第二任签名
  - 提币
  - 划转单
    - 各资产账户间的账户资产划转
  - 支付场景
    - 假设提币方提取30%以上且超过董事账户所持资产时
      - 1.验证客服账户所持资产是否满足剩余提取额度，如满足
        - 1.向客服发起支付申请，客服签名后将对应资产支付至董事账户
        - 2.向董事发起支付申请，董事签名（1+N）后，支付给提币方
      - 2.如不满足，验证系统账户所持资产是否满足剩余提取额度，如满足
        - 1.系统签名后将对应资产支付至董事账户
        - 1.向客服发起支付申请，客服签名后将对应资产支付至董事账户
        - 2.向董事发起支付申请，董事签名（1+N）后，支付给提币方
    - 假设系统账户、客服账户、董事账户任何一个无可支付资产或小于用户提取需求
      - 由董事执行，系统自动生成划账单进行账户间账务平衡
        - 董事1+N签名（或）
        - 客服签名（或）
        - 系统签名（或）
