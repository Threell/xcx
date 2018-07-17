# xcx
1.原生开发小程序，获取属性值

wxml
<view class="flex_l" wx:for="{{wealthList}}" wx:key="*this" data-navigateUrl="{{item.navigateUrl}}" bindtap="toBottomSelextIndex" ></view>

js
//获取属性值跳转，wxml是navigateUrl js是navigateurl
toBottomSelextIndex(e){
        let url = e.currentTarget.dataset.navigateurl;//（注意）
 }
 
 2.自定义组件
 组件下的json文件，这个字段必须为true；"component": true,
 
