# dabinghao123.github.com
https://cdn.letv-cdn.com/2019/02/07/Nqo6R3FOcFAjSBGI/playlist.m3u8
wangz
被支持的设备
Bootstrap 所支持的几个media queries都放在了一个文件中， 可以让你的项目更灵活的去适应不同设备和屏幕分辨率。包括：

 类型|	布局宽度	| 列宽	| 间隙宽度
------------ | ---------- | --------| --------
 大屏幕	| 大于等于1200px	| 70px	| 30px
 默认 |	大于等于980px |	60px	| 20px
 平板 |	大于等于768px |	42px	| 20px
 手机到平板 |	小于等于767px |	流式列，无固定宽度
 手机	| 小于等于480px	| 流式列，无固定宽度
 
 ##### @media screen and (max-width: 490px)
`` .feature {
    padding: 20px;
} 
@media screen and (max-width: 740px)
.feature {
    padding: 30px;
}
@media screen and (max-width: 770px)
.feature {
    padding: 50px 40px;
}
.feature {
    padding: 50px 20px;
    position: relative;
}
 ``
##### /* 大屏幕 */
##### @media (min-width: 1200px) { ... }
 
##### /* 平板电脑和小屏电脑之间的分辨率 */
##### @media (min-width: 768px) and (max-width: 979px) { ... }
 
##### /* 横向放置的手机和竖向放置的平板之间的分辨率 */
##### @media (max-width: 767px) { ... }
 
##### /* 横向放置的手机及分辨率更小的设备 */
##### @media (max-width: 480px) { ... }

