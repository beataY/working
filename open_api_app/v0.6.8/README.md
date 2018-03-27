open_api_app
==========


## Change log v0.6.9(2017/08/31)
* 新增验证用户PIN接口用例

## Change log v0.6.7(2017/08/04)
* 新增创建设备分组定时任务接口用例
* 新增获取设备分组定时任务接口用例
* 新增删除设备分组定时任务接口用例
* 新增更新设备分组定时任务接口用例
* 新增判断PK和APPID关联关系接口用例

## Change log v0.6.6(2017/07/07)
* Add case for create group
* Add case for update group
* Add case for get group
* Add case for delete group
* Add case for adding devices to group
* Add case for deleting devices from group
* Add case for get devices of group
* Add case for remoting control group devices

## Change log v0.6.5(2017/05)
* 修正远程控制接口&获取短信验证码接口的返回body
* bind by mac 接口增减支持pk为AOS_Smith_heater

## Change log v0.6.4(2017/03)
* add app check latest for new ota

## Change log v0.6.3(2017/02)
*update cases of devices_control

## Change log v0.6.2(2017/02)
* add case of anonymous users register add phone
* add case of get product datapoint（Json）

## Change log v0.6.1(2017/01)
* add case of query api_host by Timezone
* add case of query devices logs&on/offline logs
* update case of get shceduler
* add case of get api Geo mode
* add case of put api Geo mode

## Change log v0.6.0(2016/12)
* add case of ECE Apps Download 

## Change log: v0.5.8(2016/09/05)
* update test case of shceduler when date is empty&repeat is none

## Change log: v0.5.8(2016/09/05)
* Add test case of create shceduler repeat by day 
* Add test case of Get shceduler by uid
* Add test case of get shceduler log of shceduler repeat day

## Change log: v0.5.7(2016/08/12)
* Add test case of create shceduler increase enum&bin paramer 
* Add test case of Get shceduler increase enum&bin paramer
* Add test case of Get shceduler Log result increase shceduler_id

## Change log: v0.5.6(2016/07/26)
* Add test case of create shceduler increase remark field

## Change log: v0.5.5(2016/07/26)
* Add EU_env test cases

## Change log: v0.5.4(2016/07/08)
* Add test cases of wechat in API for Apps(User)
* Add test cases of Updating Bindings Info in API for Apps(Devices)

## Change log: v0.5.3(2016/5)
* bug fix：modified overseas wss/ws port value&m2m port value&&same bug fix

## Change log: v0.5.2(2016/5)
* update assersion of Bind by Mac/Get Bound Devices/Get Device Info/Device Provision

## Change log: v0.5.1(2016/5)
* Add new cases: `Sms Code` 
* update return body of Bind by Mac/Get Bound Devices/Get Device Info/Device Provision
* update cese of Create user:the same username/email/phone user register concurrent two or more time

## Change log: v0.5.0(2016/2)
* Add new cases: `Get Latest Scheduler Log` and Scheduler execute`
* add new case: `QQ register`
* add new case: `Bind by mac`
