# xcx
原生开发小程序，获取属性值

wxml
<view class="flex_l" wx:for="{{wealthList}}" wx:key="*this" data-navigateUrl="{{item.navigateUrl}}" bindtap="toBottomSelextIndex" >
    <view class="flex_l">
        <image class="img_left" src="{{item.icon}}" />
        <view class="fs32">{{item.name}}</view>
    </view>
    <view class="flex_end">
        <image class="img_next" src="/image/kd_gd.png" />
    </view>
</view>

js
//获取属性值跳转，wxml是navigateUrl js是navigateurl
toBottomSelextIndex(e){
        let url = e.currentTarget.dataset.navigateurl;//（注意）
 }
