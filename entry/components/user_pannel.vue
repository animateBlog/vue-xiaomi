<template>
	<!-- 列表 -->
    <div class="user_list">
        <div class="user_item">
            <div class="item_list vip_center">
                <div class="item_line bdb1">
                    <a href="" class="flextag item_line_taga">会员中心</a>
                </div>
            </div>
            <div class="item_list my_sale">
                <div class="item_line">
                    <a href="" class="flextag item_line_taga">我的优惠</a>
                </div>
            </div>
        </div>

        <div class="user_item">
            <div class="item_list serve_center">
                <div class="item_line bdb1">
                    <a href="" class="flextag item_line_taga">服务中心</a>
                </div>
            </div>
            <div class="item_list mi_home">
                <div class="item_line">
                    <a href="" class="flextag item_line_taga">小米之家</a>
                </div>
            </div>
        </div>

        <div class="user_item">
            <div class="item_list u_fcode">
                <div class="item_line">
                    <a href="" class="flextag item_line_taga">F码通道</a>
                </div>
            </div>
        </div>
        <div class="user_item">
            <div class="item_list u_setting">
                <div class="item_line">
                    <a href="" class="flextag item_line_taga">设置</a>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {};
</script>

<style>
/*
    列表 list
*/

.user_list {
  color: #212121;
}
.user_item {
  background: #fff;
  margin-top: 10px;
}
.item_line {
  height: 0.55rem;
  margin-left: 0.57rem;
}
.item_line a {
  justify-content: space-between;
  font-size: 0.14rem;
  line-height: 0.55rem;
  margin-right: 0.14rem;
  background: url(../images/icon/xiaomi_03.jpg) no-repeat right center;
}
.vip_center {
  background: url(../images/icon/xiaomi_18.jpg) no-repeat 0.16rem center;
}
.my_sale {
  background: url(../images/icon/xiaomi_21.jpg) no-repeat 0.16rem center;
}
.serve_center {
  background: url(../images/icon/xiaomi_23.jpg) no-repeat 0.16rem center;
}
.mi_home {
  background: url(../images/icon/xiaomi_25.jpg) no-repeat 0.16rem center;
}
.u_fcode {
  background: url(../images/icon/xiaomi_25.jpg) no-repeat 0.16rem center;
}
.u_setting {
  background: url(../images/icon/xiaomi_29.jpg) no-repeat 0.16rem center;
}
</style>
