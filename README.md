# zksyncd3.2

// 2.0数据
// ❗️ 请修改此处的RPC为私有RPC，如 Infura 或 Alchemy，否则很容易超时报错
// 定义 RPC_MAP 变量
const RPC_MAP = {
  "zks":"https://zksync2-mainnet.zksync.io"
};

// 查询 ETH 等原生资产余额
function getEthBalance(walletAddress, network) {
  let rpcLink = RPC_MAP[network];
