<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta http-equiv="X-UA-Compatible" content="IE=edge">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>jQuery四级联动商品分类代码 - 源码之家</title>

<link rel="stylesheet" href="css/qrm-pinming.css">

</head>
<body>
<center>
<!--品名开始-->
<div class="qrm-pinming">
    <div class="qrm-input-border">
        <span class="title">品名</span>
        <input type="text" placeholder="请选择" class="qrm-input" style="width: 320px">
    </div>
    <div class="qrm-pinming-panel" style="display:none">
        <div class="qrm-border">
            <ul class="qrm-lev-1 qrm-lev">
                <!--统料-->
                <li class="active">
                    <span>统料废钢</span><i class="qrm-arrow-right"></i>
                    <ul class="li-zi-1" style="display: none">
                        <li>
                            <span>统料废钢1</span><i class="qrm-arrow-right"></i>
                            <ul class="li-zi-2" style="display: none">
                                <li>
                                    <span>统料废钢1-1</span><i class="qrm-arrow-right"></i>
                                    <ul class="li-zi-3" style="display: none">
                                        <li><span>统料废钢1-1-1</span></li>
                                        <li><span>统料废钢1-1-2</span></li>
                                        <li><span>统料废钢1-1-3</span></li>
                                        <li><span>统料废钢1-1-4</span></li>
                                        <li><span>统料废钢1-1-5</span></li>
                                    </ul>
                                </li>
                                <li>
                                    <span>统料废钢1-2</span><i class="qrm-arrow-right"></i>
                                    <ul class="li-zi-3" style="display: none">
                                        <li><span>统料废钢1-2-1</span></li>
                                        <li><span>统料废钢1-2-2</span></li>
                                        <li><span>统料废钢1-2-3</span></li>
                                        <li><span>统料废钢1-2-4</span></li>
                                        <li><span>统料废钢1-2-5</span></li>
                                    </ul>
                                </li>
                                <li>
                                    <span>统料废钢1-3</span><i class="qrm-arrow-right"></i>
                                    <ul class="li-zi-3" style="display: none">
                                        <li><span>统料废钢1-3-1</span></li>
                                        <li><span>统料废钢1-3-2</span></li>
                                        <li><span>统料废钢1-3-3</span></li>
                                        <li><span>统料废钢1-3-4</span></li>
                                        <li><span>统料废钢1-3-5</span></li>
                                    </ul>
                                </li>
                                <li>
                                    <span>统料废钢1-4</span><i class="qrm-arrow-right"></i>
                                    <ul class="li-zi-3" style="display: none">
                                        <li><span>统料废钢1-4-1</span></li>
                                        <li><span>统料废钢1-4-2</span></li>
                                        <li><span>统料废钢1-4-3</span></li>
                                        <li><span>统料废钢1-4-4</span></li>
                                        <li><span>统料废钢1-4-5</span></li>
                                    </ul>
                                </li>
                                <li>
                                    <span>统料废钢1-5</span><i class="qrm-arrow-right"></i>
                                    <ul class="li-zi-3" style="display: none">
                                        <li><span>统料废钢1-5-1</span></li>
                                        <li><span>统料废钢1-5-2</span></li>
                                        <li><span>统料废钢1-5-3</span></li>
                                        <li><span>统料废钢1-5-4</span></li>
                                        <li><span>统料废钢1-5-5</span></li>
                                    </ul>
                                </li>
                            </ul>
                        </li>
                        <li>
                            <span>统料废钢2</span><i class="qrm-arrow-right"></i>
                            <ul class="li-zi-2" style="display: none">
                                <li>
                                    <span>统料废钢2-1</span><i class="qrm-arrow-right"></i>
                                    <ul class="li-zi-3" style="display: none">
                                        <li><span>统料废钢2-1-1</span></li>
                                        <li><span>统料废钢2-1-2</span></li>
                                        <li><span>统料废钢2-1-3</span></li>
                                        <li><span>统料废钢2-1-4</span></li>
                                        <li><span>统料废钢2-1-5</span></li>
                                    </ul>
                                </li>
                                <li>
                                    <span>统料废钢2-2</span><i class="qrm-arrow-right"></i>
                                    <ul class="li-zi-3" style="display: none">
                                        <li><span>统料废钢2-2-1</span></li>
                                        <li><span>统料废钢2-2-2</span></li>
                                        <li><span>统料废钢2-2-3</span></li>
                                        <li><span>统料废钢2-2-4</span></li>
                                        <li><span>统料废钢2-2-5</span></li>
                                    </ul>
                                </li>
                                <li>
                                    <span>统料废钢2-3</span><i class="qrm-arrow-right"></i>
                                    <ul class="li-zi-3" style="display: none">
                                        <li><span>统料废钢2-3-1</span></li>
                                        <li><span>统料废钢2-3-2</span></li>
                                        <li><span>统料废钢2-3-3</span></li>
                                        <li><span>统料废钢2-3-4</span></li>
                                        <li><span>统料废钢2-3-5</span></li>
                                    </ul>
                                </li>
                                <li>
                                    <span>统料废钢2-4</span><i class="qrm-arrow-right"></i>
                                    <ul class="li-zi-3" style="display: none">
                                        <li><span>统料废钢2-4-1</span></li>
                                        <li><span>统料废钢2-4-2</span></li>
                                        <li><span>统料废钢2-4-3</span></li>
                                        <li><span>统料废钢2-4-4</span></li>
                                        <li><span>统料废钢2-4-5</span></li>
                                    </ul>
                                </li>
                                <li>
                                    <span>统料废钢2-5</span><i class="qrm-arrow-right"></i>
                                    <ul class="li-zi-3" style="display: none">
                                        <li><span>统料废钢2-5-1</span></li>
                                        <li><span>统料废钢2-5-2</span></li>
                                        <li><span>统料废钢2-5-3</span></li>
                                        <li><span>统料废钢2-5-4</span></li>
                                        <li><span>统料废钢2-5-5</span></li>
                                    </ul>
                                </li>
                            </ul>
                        </li>
                        <li>
                            <span>统料废钢3</span><i class="qrm-arrow-right"></i>
                            <ul class="li-zi-2" style="display: none">
                                <li>
                                    <span>统料废钢3-1</span><i class="qrm-arrow-right"></i>
                                    <ul class="li-zi-3" style="display: none">
                                        <li><span>统料废钢3-1-1</span></li>
                                        <li><span>统料废钢3-1-2</span></li>
                                        <li><span>统料废钢3-1-3</span></li>
                                        <li><span>统料废钢3-1-4</span></li>
                                        <li><span>统料废钢3-1-5</span></li>
                                    </ul>
                                </li>
                                <li>
                                    <span>统料废钢3-2</span><i class="qrm-arrow-right"></i>
                                    <ul class="li-zi-3" style="display: none">
                                        <li><span>统料废钢3-2-1</span></li>
                                        <li><span>统料废钢3-2-2</span></li>
                                        <li><span>统料废钢3-2-3</span></li>
                                        <li><span>统料废钢3-2-4</span></li>
                                        <li><span>统料废钢3-2-5</span></li>
                                    </ul>
                                </li>
                                <li>
                                    <span>统料废钢3-3</span><i class="qrm-arrow-right"></i>
                                    <ul class="li-zi-3" style="display: none">
                                        <li><span>统料废钢3-3-1</span></li>
                                        <li><span>统料废钢3-3-2</span></li>
                                        <li><span>统料废钢3-3-3</span></li>
                                        <li><span>统料废钢3-3-4</span></li>
                                        <li><span>统料废钢3-3-5</span></li>
                                    </ul>
                                </li>
                                <li>
                                    <span>统料废钢3-4</span><i class="qrm-arrow-right"></i>
                                    <ul class="li-zi-3" style="display: none">
                                        <li><span>统料废钢3-4-1</span></li>
                                        <li><span>统料废钢3-4-2</span></li>
                                        <li><span>统料废钢3-4-3</span></li>
                                        <li><span>统料废钢3-4-4</span></li>
                                        <li><span>统料废钢3-4-5</span></li>
                                    </ul>
                                </li>
                                <li>
                                    <span>统料废钢3-5</span><i class="qrm-arrow-right"></i>
                                    <ul class="li-zi-3" style="display: none">
                                        <li><span>统料废钢3-5-1</span></li>
                                        <li><span>统料废钢3-5-2</span></li>
                                        <li><span>统料废钢3-5-3</span></li>
                                        <li><span>统料废钢3-5-4</span></li>
                                        <li><span>统料废钢3-5-5</span></li>
                                    </ul>
                                </li>
                            </ul>
                        </li>
                        <li>
                            <span>统料废钢4</span><i class="qrm-arrow-right"></i>
                            <ul class="li-zi-2" style="display: none">
                                <li>
                                    <span>统料废钢4-1</span><i class="qrm-arrow-right"></i>
                                    <ul class="li-zi-3" style="display: none">
                                        <li><span>统料废钢4-1-1</span></li>
                                        <li><span>统料废钢4-1-2</span></li>
                                        <li><span>统料废钢4-1-3</span></li>
                                        <li><span>统料废钢4-1-4</span></li>
                                        <li><span>统料废钢4-1-5</span></li>
                                    </ul>
                                </li>
                                <li>
                                    <span>统料废钢4-2</span><i class="qrm-arrow-right"></i>
                                    <ul class="li-zi-3" style="display: none">
                                        <li><span>统料废钢4-2-1</span></li>
                                        <li><span>统料废钢4-2-2</span></li>
                                        <li><span>统料废钢4-2-3</span></li>
                                        <li><span>统料废钢4-2-4</span></li>
                                        <li><span>统料废钢4-2-5</span></li>
                                    </ul>
                                </li>
                                <li>
                                    <span>统料废钢4-3</span><i class="qrm-arrow-right"></i>
                                    <ul class="li-zi-3" style="display: none">
                                        <li><span>统料废钢4-3-1</span></li>
                                        <li><span>统料废钢4-3-2</span></li>
                                        <li><span>统料废钢4-3-3</span></li>
                                        <li><span>统料废钢4-3-4</span></li>
                                        <li><span>统料废钢4-3-5</span></li>
                                    </ul>
                                </li>
                                <li>
                                    <span>统料废钢4-4</span><i class="qrm-arrow-right"></i>
                                    <ul class="li-zi-3" style="display: none">
                                        <li><span>统料废钢4-4-1</span></li>
                                        <li><span>统料废钢4-4-2</span></li>
                                        <li><span>统料废钢4-4-3</span></li>
                                        <li><span>统料废钢4-4-4</span></li>
                                        <li><span>统料废钢4-4-5</span></li>
                                    </ul>
                                </li>
                                <li>
                                    <span>统料废钢4-5</span><i class="qrm-arrow-right"></i>
                                    <ul class="li-zi-3" style="display: none">
                                        <li><span>统料废钢4-5-1</span></li>
                                        <li><span>统料废钢4-5-2</span></li>
                                        <li><span>统料废钢4-5-3</span></li>
                                        <li><span>统料废钢4-5-4</span></li>
                                        <li><span>统料废钢4-5-5</span></li>
                                    </ul>
                                </li>
                            </ul>
                        </li>
                        <li>
                            <span>统料废钢5</span><i class="qrm-arrow-right"></i>
                            <ul class="li-zi-2" style="display: none">
                                <li>
                                    <span>统料废钢5-1</span><i class="qrm-arrow-right"></i>
                                    <ul class="li-zi-3" style="display: none">
                                        <li><span>统料废钢5-1-1</span></li>
                                        <li><span>统料废钢5-1-2</span></li>
                                        <li><span>统料废钢5-1-3</span></li>
                                        <li><span>统料废钢5-1-4</span></li>
                                        <li><span>统料废钢5-1-5</span></li>
                                    </ul>
                                </li>
                                <li>
                                    <span>统料废钢5-2</span><i class="qrm-arrow-right"></i>
                                    <ul class="li-zi-3" style="display: none">
                                        <li><span>统料废钢5-2-1</span></li>
                                        <li><span>统料废钢5-2-2</span></li>
                                        <li><span>统料废钢5-2-3</span></li>
                                        <li><span>统料废钢5-2-4</span></li>
                                        <li><span>统料废钢5-2-5</span></li>
                                    </ul>
                                </li>
                                <li>
                                    <span>统料废钢5-3</span><i class="qrm-arrow-right"></i>
                                    <ul class="li-zi-3" style="display: none">
                                        <li><span>统料废钢5-3-1</span></li>
                                        <li><span>统料废钢5-3-2</span></li>
                                        <li><span>统料废钢5-3-3</span></li>
                                        <li><span>统料废钢5-3-4</span></li>
                                        <li><span>统料废钢5-3-5</span></li>
                                    </ul>
                                </li>
                                <li>
                                    <span>统料废钢5-4</span><i class="qrm-arrow-right"></i>
                                    <ul class="li-zi-3" style="display: none">
                                        <li><span>统料废钢5-4-1</span></li>
                                        <li><span>统料废钢5-4-2</span></li>
                                        <li><span>统料废钢5-4-3</span></li>
                                        <li><span>统料废钢5-4-4</span></li>
                                        <li><span>统料废钢5-4-5</span></li>
                                    </ul>
                                </li>
                                <li>
                                    <span>统料废钢5-5</span><i class="qrm-arrow-right"></i>
                                    <ul class="li-zi-3" style="display: none">
                                        <li><span>统料废钢5-5-1</span></li>
                                        <li><span>统料废钢5-5-2</span></li>
                                        <li><span>统料废钢5-5-3</span></li>
                                        <li><span>统料废钢5-5-4</span></li>
                                        <li><span>统料废钢5-5-5</span></li>
                                    </ul>
                                </li>
                            </ul>
                        </li>
                    </ul>
                </li>
                <!--重型-->
                <li>
                    <span>重型废钢</span><i class="qrm-arrow-right"></i>
                    <ul class="li-zi-1" style="display: none">
                        <li>
                            <span>重型废钢1</span><i class="qrm-arrow-right"></i>
                            <ul class="li-zi-2" style="display: none">
                                <li>
                                    <span>重型废钢1-1</span><i class="qrm-arrow-right"></i>
                                    <ul class="li-zi-3" style="display: none">
                                        <li><span>重型废钢1-1-1</span></li>
                                        <li><span>重型废钢1-1-2</span></li>
                                        <li><span>重型废钢1-1-3</span></li>
                                        <li><span>重型废钢1-1-4</span></li>
                                        <li><span>重型废钢1-1-5</span></li>
                                    </ul>
                                </li>
                                <li>
                                    <span>重型废钢1-2</span><i class="qrm-arrow-right"></i>
                                    <ul class="li-zi-3" style="display: none">
                                        <li><span>重型废钢1-2-1</span></li>
                                        <li><span>重型废钢1-2-2</span></li>
                                        <li><span>重型废钢1-2-3</span></li>
                                        <li><span>重型废钢1-2-4</span></li>
                                        <li><span>重型废钢1-2-5</span></li>
                                    </ul>
                                </li>
                                <li>
                                    <span>重型废钢1-3</span><i class="qrm-arrow-right"></i>
                                    <ul class="li-zi-3" style="display: none">
                                        <li><span>重型废钢1-3-1</span></li>
                                        <li><span>重型废钢1-3-2</span></li>
                                        <li><span>重型废钢1-3-3</span></li>
                                        <li><span>重型废钢1-3-4</span></li>
                                        <li><span>重型废钢1-3-5</span></li>
                                    </ul>
                                </li>
                                <li>
                                    <span>重型废钢1-4</span><i class="qrm-arrow-right"></i>
                                    <ul class="li-zi-3" style="display: none">
                                        <li><span>重型废钢1-4-1</span></li>
                                        <li><span>重型废钢1-4-2</span></li>
                                        <li><span>重型废钢1-4-3</span></li>
                                        <li><span>重型废钢1-4-4</span></li>
                                        <li><span>重型废钢1-4-5</span></li>
                                    </ul>
                                </li>
                                <li>
                                    <span>重型废钢1-5</span><i class="qrm-arrow-right"></i>
                                    <ul class="li-zi-3" style="display: none">
                                        <li><span>重型废钢1-5-1</span></li>
                                        <li><span>重型废钢1-5-2</span></li>
                                        <li><span>重型废钢1-5-3</span></li>
                                        <li><span>重型废钢1-5-4</span></li>
                                        <li><span>重型废钢1-5-5</span></li>
                                    </ul>
                                </li>
                            </ul>
                        </li>
                        <li>
                            <span>重型废钢2</span><i class="qrm-arrow-right"></i>
                            <ul class="li-zi-2" style="display: none">
                                <li>
                                    <span>重型废钢2-1</span><i class="qrm-arrow-right"></i>
                                    <ul class="li-zi-3" style="display: none">
                                        <li><span>重型废钢2-1-1</span></li>
                                        <li><span>重型废钢2-1-2</span></li>
                                        <li><span>重型废钢2-1-3</span></li>
                                        <li><span>重型废钢2-1-4</span></li>
                                        <li><span>重型废钢2-1-5</span></li>
                                    </ul>
                                </li>
                                <li>
                                    <span>重型废钢2-2</span><i class="qrm-arrow-right"></i>
                                    <ul class="li-zi-3" style="display: none">
                                        <li><span>重型废钢2-2-1</span></li>
                                        <li><span>重型废钢2-2-2</span></li>
                                        <li><span>重型废钢2-2-3</span></li>
                                        <li><span>重型废钢2-2-4</span></li>
                                        <li><span>重型废钢2-2-5</span></li>
                                    </ul>
                                </li>
                                <li>
                                    <span>重型废钢2-3</span><i class="qrm-arrow-right"></i>
                                    <ul class="li-zi-3" style="display: none">
                                        <li><span>重型废钢2-3-1</span></li>
                                        <li><span>重型废钢2-3-2</span></li>
                                        <li><span>重型废钢2-3-3</span></li>
                                        <li><span>重型废钢2-3-4</span></li>
                                        <li><span>重型废钢2-3-5</span></li>
                                    </ul>
                                </li>
                                <li>
                                    <span>重型废钢2-4</span><i class="qrm-arrow-right"></i>
                                    <ul class="li-zi-3" style="display: none">
                                        <li><span>重型废钢2-4-1</span></li>
                                        <li><span>重型废钢2-4-2</span></li>
                                        <li><span>重型废钢2-4-3</span></li>
                                        <li><span>重型废钢2-4-4</span></li>
                                        <li><span>重型废钢2-4-5</span></li>
                                    </ul>
                                </li>
                                <li>
                                    <span>重型废钢2-5</span><i class="qrm-arrow-right"></i>
                                    <ul class="li-zi-3" style="display: none">
                                        <li><span>重型废钢2-5-1</span></li>
                                        <li><span>重型废钢2-5-2</span></li>
                                        <li><span>重型废钢2-5-3</span></li>
                                        <li><span>重型废钢2-5-4</span></li>
                                        <li><span>重型废钢2-5-5</span></li>
                                    </ul>
                                </li>
                            </ul>
                        </li>
                        <li>
                            <span>重型废钢3</span><i class="qrm-arrow-right"></i>
                            <ul class="li-zi-2" style="display: none">
                                <li>
                                    <span>重型废钢3-1</span><i class="qrm-arrow-right"></i>
                                    <ul class="li-zi-3" style="display: none">
                                        <li><span>重型废钢3-1-1</span></li>
                                        <li><span>重型废钢3-1-2</span></li>
                                        <li><span>重型废钢3-1-3</span></li>
                                        <li><span>重型废钢3-1-4</span></li>
                                        <li><span>重型废钢3-1-5</span></li>
                                    </ul>
                                </li>
                                <li>
                                    <span>重型废钢3-2</span><i class="qrm-arrow-right"></i>
                                    <ul class="li-zi-3" style="display: none">
                                        <li><span>重型废钢3-2-1</span></li>
                                        <li><span>重型废钢3-2-2</span></li>
                                        <li><span>重型废钢3-2-3</span></li>
                                        <li><span>重型废钢3-2-4</span></li>
                                        <li><span>重型废钢3-2-5</span></li>
                                    </ul>
                                </li>
                                <li>
                                    <span>重型废钢3-3</span><i class="qrm-arrow-right"></i>
                                    <ul class="li-zi-3" style="display: none">
                                        <li><span>重型废钢3-3-1</span></li>
                                        <li><span>重型废钢3-3-2</span></li>
                                        <li><span>重型废钢3-3-3</span></li>
                                        <li><span>重型废钢3-3-4</span></li>
                                        <li><span>重型废钢3-3-5</span></li>
                                    </ul>
                                </li>
                                <li>
                                    <span>重型废钢3-4</span><i class="qrm-arrow-right"></i>
                                    <ul class="li-zi-3" style="display: none">
                                        <li><span>重型废钢3-4-1</span></li>
                                        <li><span>重型废钢3-4-2</span></li>
                                        <li><span>重型废钢3-4-3</span></li>
                                        <li><span>重型废钢3-4-4</span></li>
                                        <li><span>重型废钢3-4-5</span></li>
                                    </ul>
                                </li>
                                <li>
                                    <span>重型废钢3-5</span><i class="qrm-arrow-right"></i>
                                    <ul class="li-zi-3" style="display: none">
                                        <li><span>重型废钢3-5-1</span></li>
                                        <li><span>重型废钢3-5-2</span></li>
                                        <li><span>重型废钢3-5-3</span></li>
                                        <li><span>重型废钢3-5-4</span></li>
                                        <li><span>重型废钢3-5-5</span></li>
                                    </ul>
                                </li>
                            </ul>
                        </li>
                        <li>
                            <span>重型废钢4</span><i class="qrm-arrow-right"></i>
                            <ul class="li-zi-2" style="display: none">
                                <li>
                                    <span>重型废钢4-1</span><i class="qrm-arrow-right"></i>
                                    <ul class="li-zi-3" style="display: none">
                                        <li><span>重型废钢4-1-1</span></li>
                                        <li><span>重型废钢4-1-2</span></li>
                                        <li><span>重型废钢4-1-3</span></li>
                                        <li><span>重型废钢4-1-4</span></li>
                                        <li><span>重型废钢4-1-5</span></li>
                                    </ul>
                                </li>
                                <li>
                                    <span>重型废钢4-2</span><i class="qrm-arrow-right"></i>
                                    <ul class="li-zi-3" style="display: none">
                                        <li><span>重型废钢4-2-1</span></li>
                                        <li><span>重型废钢4-2-2</span></li>
                                        <li><span>重型废钢4-2-3</span></li>
                                        <li><span>重型废钢4-2-4</span></li>
                                        <li><span>重型废钢4-2-5</span></li>
                                    </ul>
                                </li>
                                <li>
                                    <span>重型废钢4-3</span><i class="qrm-arrow-right"></i>
                                    <ul class="li-zi-3" style="display: none">
                                        <li><span>重型废钢4-3-1</span></li>
                                        <li><span>重型废钢4-3-2</span></li>
                                        <li><span>重型废钢4-3-3</span></li>
                                        <li><span>重型废钢4-3-4</span></li>
                                        <li><span>重型废钢4-3-5</span></li>
                                    </ul>
                                </li>
                                <li>
                                    <span>重型废钢4-4</span><i class="qrm-arrow-right"></i>
                                    <ul class="li-zi-3" style="display: none">
                                        <li><span>重型废钢4-4-1</span></li>
                                        <li><span>重型废钢4-4-2</span></li>
                                        <li><span>重型废钢4-4-3</span></li>
                                        <li><span>重型废钢4-4-4</span></li>
                                        <li><span>重型废钢4-4-5</span></li>
                                    </ul>
                                </li>
                                <li>
                                    <span>重型废钢4-5</span><i class="qrm-arrow-right"></i>
                                    <ul class="li-zi-3" style="display: none">
                                        <li><span>重型废钢4-5-1</span></li>
                                        <li><span>重型废钢4-5-2</span></li>
                                        <li><span>重型废钢4-5-3</span></li>
                                        <li><span>重型废钢4-5-4</span></li>
                                        <li><span>重型废钢4-5-5</span></li>
                                    </ul>
                                </li>
                            </ul>
                        </li>
                        <li>
                            <span>重型废钢5</span><i class="qrm-arrow-right"></i>
                            <ul class="li-zi-2" style="display: none">
                                <li>
                                    <span>重型废钢5-1</span><i class="qrm-arrow-right"></i>
                                    <ul class="li-zi-3" style="display: none">
                                        <li><span>重型废钢5-1-1</span></li>
                                        <li><span>重型废钢5-1-2</span></li>
                                        <li><span>重型废钢5-1-3</span></li>
                                        <li><span>重型废钢5-1-4</span></li>
                                        <li><span>重型废钢5-1-5</span></li>
                                    </ul>
                                </li>
                                <li>
                                    <span>重型废钢5-2</span><i class="qrm-arrow-right"></i>
                                    <ul class="li-zi-3" style="display: none">
                                        <li><span>重型废钢5-2-1</span></li>
                                        <li><span>重型废钢5-2-2</span></li>
                                        <li><span>重型废钢5-2-3</span></li>
                                        <li><span>重型废钢5-2-4</span></li>
                                        <li><span>重型废钢5-2-5</span></li>
                                    </ul>
                                </li>
                                <li>
                                    <span>重型废钢5-3</span><i class="qrm-arrow-right"></i>
                                    <ul class="li-zi-3" style="display: none">
                                        <li><span>重型废钢5-3-1</span></li>
                                        <li><span>重型废钢5-3-2</span></li>
                                        <li><span>重型废钢5-3-3</span></li>
                                        <li><span>重型废钢5-3-4</span></li>
                                        <li><span>重型废钢5-3-5</span></li>
                                    </ul>
                                </li>
                                <li>
                                    <span>重型废钢5-4</span><i class="qrm-arrow-right"></i>
                                    <ul class="li-zi-3" style="display: none">
                                        <li><span>重型废钢5-4-1</span></li>
                                        <li><span>重型废钢5-4-2</span></li>
                                        <li><span>重型废钢5-4-3</span></li>
                                        <li><span>重型废钢5-4-4</span></li>
                                        <li><span>重型废钢5-4-5</span></li>
                                    </ul>
                                </li>
                                <li>
                                    <span>重型废钢5-5</span><i class="qrm-arrow-right"></i>
                                    <ul class="li-zi-3" style="display: none">
                                        <li><span>重型废钢5-5-1</span></li>
                                        <li><span>重型废钢5-5-2</span></li>
                                        <li><span>重型废钢5-5-3</span></li>
                                        <li><span>重型废钢5-5-4</span></li>
                                        <li><span>重型废钢5-5-5</span></li>
                                    </ul>
                                </li>
                            </ul>
                        </li>
                    </ul>
                </li>
                <!--中型-->
                <li>
                    <span>中型废钢</span><i class="qrm-arrow-right"></i>
                    <ul class="li-zi-1" style="display: none">
                        <li>
                            <span>中型废钢1</span><i class="qrm-arrow-right"></i>
                            <ul class="li-zi-2" style="display: none">
                                <li>
                                    <span>中型废钢1-1</span><i class="qrm-arrow-right"></i>
                                    <ul class="li-zi-3" style="display: none">
                                        <li><span>中型废钢1-1-1</span></li>
                                        <li><span>中型废钢1-1-2</span></li>
                                        <li><span>中型废钢1-1-3</span></li>
                                        <li><span>中型废钢1-1-4</span></li>
                                        <li><span>中型废钢1-1-5</span></li>
                                    </ul>
                                </li>
                                <li>
                                    <span>中型废钢1-2</span><i class="qrm-arrow-right"></i>
                                    <ul class="li-zi-3" style="display: none">
                                        <li><span>中型废钢1-2-1</span></li>
                                        <li><span>中型废钢1-2-2</span></li>
                                        <li><span>中型废钢1-2-3</span></li>
                                        <li><span>中型废钢1-2-4</span></li>
                                        <li><span>中型废钢1-2-5</span></li>
                                    </ul>
                                </li>
                                <li>
                                    <span>中型废钢1-3</span><i class="qrm-arrow-right"></i>
                                    <ul class="li-zi-3" style="display: none">
                                        <li><span>中型废钢1-3-1</span></li>
                                        <li><span>中型废钢1-3-2</span></li>
                                        <li><span>中型废钢1-3-3</span></li>
                                        <li><span>中型废钢1-3-4</span></li>
                                        <li><span>中型废钢1-3-5</span></li>
                                    </ul>
                                </li>
                                <li>
                                    <span>中型废钢1-4</span><i class="qrm-arrow-right"></i>
                                    <ul class="li-zi-3" style="display: none">
                                        <li><span>中型废钢1-4-1</span></li>
                                        <li><span>中型废钢1-4-2</span></li>
                                        <li><span>中型废钢1-4-3</span></li>
                                        <li><span>中型废钢1-4-4</span></li>
                                        <li><span>中型废钢1-4-5</span></li>
                                    </ul>
                                </li>
                                <li>
                                    <span>中型废钢1-5</span><i class="qrm-arrow-right"></i>
                                    <ul class="li-zi-3" style="display: none">
                                        <li><span>中型废钢1-5-1</span></li>
                                        <li><span>中型废钢1-5-2</span></li>
                                        <li><span>中型废钢1-5-3</span></li>
                                        <li><span>中型废钢1-5-4</span></li>
                                        <li><span>中型废钢1-5-5</span></li>
                                    </ul>
                                </li>
                            </ul>
                        </li>
                        <li>
                            <span>中型废钢2</span><i class="qrm-arrow-right"></i>
                            <ul class="li-zi-2" style="display: none">
                                <li>
                                    <span>中型废钢2-1</span><i class="qrm-arrow-right"></i>
                                    <ul class="li-zi-3" style="display: none">
                                        <li><span>中型废钢2-1-1</span></li>
                                        <li><span>中型废钢2-1-2</span></li>
                                        <li><span>中型废钢2-1-3</span></li>
                                        <li><span>中型废钢2-1-4</span></li>
                                        <li><span>中型废钢2-1-5</span></li>
                                    </ul>
                                </li>
                                <li>
                                    <span>中型废钢2-2</span><i class="qrm-arrow-right"></i>
                                    <ul class="li-zi-3" style="display: none">
                                        <li><span>中型废钢2-2-1</span></li>
                                        <li><span>中型废钢2-2-2</span></li>
                                        <li><span>中型废钢2-2-3</span></li>
                                        <li><span>中型废钢2-2-4</span></li>
                                        <li><span>中型废钢2-2-5</span></li>
                                    </ul>
                                </li>
                                <li>
                                    <span>中型废钢2-3</span><i class="qrm-arrow-right"></i>
                                    <ul class="li-zi-3" style="display: none">
                                        <li><span>中型废钢2-3-1</span></li>
                                        <li><span>中型废钢2-3-2</span></li>
                                        <li><span>中型废钢2-3-3</span></li>
                                        <li><span>中型废钢2-3-4</span></li>
                                        <li><span>中型废钢2-3-5</span></li>
                                    </ul>
                                </li>
                                <li>
                                    <span>中型废钢2-4</span><i class="qrm-arrow-right"></i>
                                    <ul class="li-zi-3" style="display: none">
                                        <li><span>中型废钢2-4-1</span></li>
                                        <li><span>中型废钢2-4-2</span></li>
                                        <li><span>中型废钢2-4-3</span></li>
                                        <li><span>中型废钢2-4-4</span></li>
                                        <li><span>中型废钢2-4-5</span></li>
                                    </ul>
                                </li>
                                <li>
                                    <span>中型废钢2-5</span><i class="qrm-arrow-right"></i>
                                    <ul class="li-zi-3" style="display: none">
                                        <li><span>中型废钢2-5-1</span></li>
                                        <li><span>中型废钢2-5-2</span></li>
                                        <li><span>中型废钢2-5-3</span></li>
                                        <li><span>中型废钢2-5-4</span></li>
                                        <li><span>中型废钢2-5-5</span></li>
                                    </ul>
                                </li>
                            </ul>
                        </li>
                        <li>
                            <span>中型废钢3</span><i class="qrm-arrow-right"></i>
                            <ul class="li-zi-2" style="display: none">
                                <li>
                                    <span>中型废钢3-1</span><i class="qrm-arrow-right"></i>
                                    <ul class="li-zi-3" style="display: none">
                                        <li><span>中型废钢3-1-1</span></li>
                                        <li><span>中型废钢3-1-2</span></li>
                                        <li><span>中型废钢3-1-3</span></li>
                                        <li><span>中型废钢3-1-4</span></li>
                                        <li><span>中型废钢3-1-5</span></li>
                                    </ul>
                                </li>
                                <li>
                                    <span>中型废钢3-2</span><i class="qrm-arrow-right"></i>
                                    <ul class="li-zi-3" style="display: none">
                                        <li><span>中型废钢3-2-1</span></li>
                                        <li><span>中型废钢3-2-2</span></li>
                                        <li><span>中型废钢3-2-3</span></li>
                                        <li><span>中型废钢3-2-4</span></li>
                                        <li><span>中型废钢3-2-5</span></li>
                                    </ul>
                                </li>
                                <li>
                                    <span>中型废钢3-3</span><i class="qrm-arrow-right"></i>
                                    <ul class="li-zi-3" style="display: none">
                                        <li><span>中型废钢3-3-1</span></li>
                                        <li><span>中型废钢3-3-2</span></li>
                                        <li><span>中型废钢3-3-3</span></li>
                                        <li><span>中型废钢3-3-4</span></li>
                                        <li><span>中型废钢3-3-5</span></li>
                                    </ul>
                                </li>
                                <li>
                                    <span>中型废钢3-4</span><i class="qrm-arrow-right"></i>
                                    <ul class="li-zi-3" style="display: none">
                                        <li><span>中型废钢3-4-1</span></li>
                                        <li><span>中型废钢3-4-2</span></li>
                                        <li><span>中型废钢3-4-3</span></li>
                                        <li><span>中型废钢3-4-4</span></li>
                                        <li><span>中型废钢3-4-5</span></li>
                                    </ul>
                                </li>
                                <li>
                                    <span>中型废钢3-5</span><i class="qrm-arrow-right"></i>
                                    <ul class="li-zi-3" style="display: none">
                                        <li><span>中型废钢3-5-1</span></li>
                                        <li><span>中型废钢3-5-2</span></li>
                                        <li><span>中型废钢3-5-3</span></li>
                                        <li><span>中型废钢3-5-4</span></li>
                                        <li><span>中型废钢3-5-5</span></li>
                                    </ul>
                                </li>
                            </ul>
                        </li>
                        <li>
                            <span>中型废钢4</span><i class="qrm-arrow-right"></i>
                            <ul class="li-zi-2" style="display: none">
                                <li>
                                    <span>中型废钢4-1</span><i class="qrm-arrow-right"></i>
                                    <ul class="li-zi-3" style="display: none">
                                        <li><span>中型废钢4-1-1</span></li>
                                        <li><span>中型废钢4-1-2</span></li>
                                        <li><span>中型废钢4-1-3</span></li>
                                        <li><span>中型废钢4-1-4</span></li>
                                        <li><span>中型废钢4-1-5</span></li>
                                    </ul>
                                </li>
                                <li>
                                    <span>中型废钢4-2</span><i class="qrm-arrow-right"></i>
                                    <ul class="li-zi-3" style="display: none">
                                        <li><span>中型废钢4-2-1</span></li>
                                        <li><span>中型废钢4-2-2</span></li>
                                        <li><span>中型废钢4-2-3</span></li>
                                        <li><span>中型废钢4-2-4</span></li>
                                        <li><span>中型废钢4-2-5</span></li>
                                    </ul>
                                </li>
                                <li>
                                    <span>中型废钢4-3</span><i class="qrm-arrow-right"></i>
                                    <ul class="li-zi-3" style="display: none">
                                        <li><span>中型废钢4-3-1</span></li>
                                        <li><span>中型废钢4-3-2</span></li>
                                        <li><span>中型废钢4-3-3</span></li>
                                        <li><span>中型废钢4-3-4</span></li>
                                        <li><span>中型废钢4-3-5</span></li>
                                    </ul>
                                </li>
                                <li>
                                    <span>中型废钢4-4</span><i class="qrm-arrow-right"></i>
                                    <ul class="li-zi-3" style="display: none">
                                        <li><span>中型废钢4-4-1</span></li>
                                        <li><span>中型废钢4-4-2</span></li>
                                        <li><span>中型废钢4-4-3</span></li>
                                        <li><span>中型废钢4-4-4</span></li>
                                        <li><span>中型废钢4-4-5</span></li>
                                    </ul>
                                </li>
                                <li>
                                    <span>中型废钢4-5</span><i class="qrm-arrow-right"></i>
                                    <ul class="li-zi-3" style="display: none">
                                        <li><span>中型废钢4-5-1</span></li>
                                        <li><span>中型废钢4-5-2</span></li>
                                        <li><span>中型废钢4-5-3</span></li>
                                        <li><span>中型废钢4-5-4</span></li>
                                        <li><span>中型废钢4-5-5</span></li>
                                    </ul>
                                </li>
                            </ul>
                        </li>
                        <li>
                            <span>中型废钢5</span><i class="qrm-arrow-right"></i>
                            <ul class="li-zi-2" style="display: none">
                                <li>
                                    <span>中型废钢5-1</span><i class="qrm-arrow-right"></i>
                                    <ul class="li-zi-3" style="display: none">
                                        <li><span>中型废钢5-1-1</span></li>
                                        <li><span>中型废钢5-1-2</span></li>
                                        <li><span>中型废钢5-1-3</span></li>
                                        <li><span>中型废钢5-1-4</span></li>
                                        <li><span>中型废钢5-1-5</span></li>
                                    </ul>
                                </li>
                                <li>
                                    <span>中型废钢5-2</span><i class="qrm-arrow-right"></i>
                                    <ul class="li-zi-3" style="display: none">
                                        <li><span>中型废钢5-2-1</span></li>
                                        <li><span>中型废钢5-2-2</span></li>
                                        <li><span>中型废钢5-2-3</span></li>
                                        <li><span>中型废钢5-2-4</span></li>
                                        <li><span>中型废钢5-2-5</span></li>
                                    </ul>
                                </li>
                                <li>
                                    <span>中型废钢5-3</span><i class="qrm-arrow-right"></i>
                                    <ul class="li-zi-3" style="display: none">
                                        <li><span>中型废钢5-3-1</span></li>
                                        <li><span>中型废钢5-3-2</span></li>
                                        <li><span>中型废钢5-3-3</span></li>
                                        <li><span>中型废钢5-3-4</span></li>
                                        <li><span>中型废钢5-3-5</span></li>
                                    </ul>
                                </li>
                                <li>
                                    <span>中型废钢5-4</span><i class="qrm-arrow-right"></i>
                                    <ul class="li-zi-3" style="display: none">
                                        <li><span>中型废钢5-4-1</span></li>
                                        <li><span>中型废钢5-4-2</span></li>
                                        <li><span>中型废钢5-4-3</span></li>
                                        <li><span>中型废钢5-4-4</span></li>
                                        <li><span>中型废钢5-4-5</span></li>
                                    </ul>
                                </li>
                                <li>
                                    <span>中型废钢5-5</span><i class="qrm-arrow-right"></i>
                                    <ul class="li-zi-3" style="display: none">
                                        <li><span>中型废钢5-5-1</span></li>
                                        <li><span>中型废钢5-5-2</span></li>
                                        <li><span>中型废钢5-5-3</span></li>
                                        <li><span>中型废钢5-5-4</span></li>
                                        <li><span>中型废钢5-5-5</span></li>
                                    </ul>
                                </li>
                            </ul>
                        </li>
                    </ul>
                </li>
                <!--小型-->
                <li>
                    <span>小型废钢</span><i class="qrm-arrow-right"></i>
                    <ul class="li-zi-1" style="display: none">
                        <li>
                            <span>小型废钢1</span><i class="qrm-arrow-right"></i>
                            <ul class="li-zi-2" style="display: none">
                                <li>
                                    <span>小型废钢1-1</span><i class="qrm-arrow-right"></i>
                                    <ul class="li-zi-3" style="display: none">
                                        <li><span>小型废钢1-1-1</span></li>
                                        <li><span>小型废钢1-1-2</span></li>
                                        <li><span>小型废钢1-1-3</span></li>
                                        <li><span>小型废钢1-1-4</span></li>
                                        <li><span>小型废钢1-1-5</span></li>
                                    </ul>
                                </li>
                                <li>
                                    <span>小型废钢1-2</span><i class="qrm-arrow-right"></i>
                                    <ul class="li-zi-3" style="display: none">
                                        <li><span>小型废钢1-2-1</span></li>
                                        <li><span>小型废钢1-2-2</span></li>
                                        <li><span>小型废钢1-2-3</span></li>
                                        <li><span>小型废钢1-2-4</span></li>
                                        <li><span>小型废钢1-2-5</span></li>
                                    </ul>
                                </li>
                                <li>
                                    <span>小型废钢1-3</span><i class="qrm-arrow-right"></i>
                                    <ul class="li-zi-3" style="display: none">
                                        <li><span>小型废钢1-3-1</span></li>
                                        <li><span>小型废钢1-3-2</span></li>
                                        <li><span>小型废钢1-3-3</span></li>
                                        <li><span>小型废钢1-3-4</span></li>
                                        <li><span>小型废钢1-3-5</span></li>
                                    </ul>
                                </li>
                                <li>
                                    <span>小型废钢1-4</span><i class="qrm-arrow-right"></i>
                                    <ul class="li-zi-3" style="display: none">
                                        <li><span>小型废钢1-4-1</span></li>
                                        <li><span>小型废钢1-4-2</span></li>
                                        <li><span>小型废钢1-4-3</span></li>
                                        <li><span>小型废钢1-4-4</span></li>
                                        <li><span>小型废钢1-4-5</span></li>
                                    </ul>
                                </li>
                                <li>
                                    <span>小型废钢1-5</span><i class="qrm-arrow-right"></i>
                                    <ul class="li-zi-3" style="display: none">
                                        <li><span>小型废钢1-5-1</span></li>
                                        <li><span>小型废钢1-5-2</span></li>
                                        <li><span>小型废钢1-5-3</span></li>
                                        <li><span>小型废钢1-5-4</span></li>
                                        <li><span>小型废钢1-5-5</span></li>
                                    </ul>
                                </li>
                            </ul>
                        </li>
                        <li>
                            <span>小型废钢2</span><i class="qrm-arrow-right"></i>
                            <ul class="li-zi-2" style="display: none">
                                <li>
                                    <span>小型废钢2-1</span><i class="qrm-arrow-right"></i>
                                    <ul class="li-zi-3" style="display: none">
                                        <li><span>小型废钢2-1-1</span></li>
                                        <li><span>小型废钢2-1-2</span></li>
                                        <li><span>小型废钢2-1-3</span></li>
                                        <li><span>小型废钢2-1-4</span></li>
                                        <li><span>小型废钢2-1-5</span></li>
                                    </ul>
                                </li>
                                <li>
                                    <span>小型废钢2-2</span><i class="qrm-arrow-right"></i>
                                    <ul class="li-zi-3" style="display: none">
                                        <li><span>小型废钢2-2-1</span></li>
                                        <li><span>小型废钢2-2-2</span></li>
                                        <li><span>小型废钢2-2-3</span></li>
                                        <li><span>小型废钢2-2-4</span></li>
                                        <li><span>小型废钢2-2-5</span></li>
                                    </ul>
                                </li>
                                <li>
                                    <span>小型废钢2-3</span><i class="qrm-arrow-right"></i>
                                    <ul class="li-zi-3" style="display: none">
                                        <li><span>小型废钢2-3-1</span></li>
                                        <li><span>小型废钢2-3-2</span></li>
                                        <li><span>小型废钢2-3-3</span></li>
                                        <li><span>小型废钢2-3-4</span></li>
                                        <li><span>小型废钢2-3-5</span></li>
                                    </ul>
                                </li>
                                <li>
                                    <span>小型废钢2-4</span><i class="qrm-arrow-right"></i>
                                    <ul class="li-zi-3" style="display: none">
                                        <li><span>小型废钢2-4-1</span></li>
                                        <li><span>小型废钢2-4-2</span></li>
                                        <li><span>小型废钢2-4-3</span></li>
                                        <li><span>小型废钢2-4-4</span></li>
                                        <li><span>小型废钢2-4-5</span></li>
                                    </ul>
                                </li>
                                <li>
                                    <span>小型废钢2-5</span><i class="qrm-arrow-right"></i>
                                    <ul class="li-zi-3" style="display: none">
                                        <li><span>小型废钢2-5-1</span></li>
                                        <li><span>小型废钢2-5-2</span></li>
                                        <li><span>小型废钢2-5-3</span></li>
                                        <li><span>小型废钢2-5-4</span></li>
                                        <li><span>小型废钢2-5-5</span></li>
                                    </ul>
                                </li>
                            </ul>
                        </li>
                        <li>
                            <span>小型废钢3</span><i class="qrm-arrow-right"></i>
                            <ul class="li-zi-2" style="display: none">
                                <li>
                                    <span>小型废钢3-1</span><i class="qrm-arrow-right"></i>
                                    <ul class="li-zi-3" style="display: none">
                                        <li><span>小型废钢3-1-1</span></li>
                                        <li><span>小型废钢3-1-2</span></li>
                                        <li><span>小型废钢3-1-3</span></li>
                                        <li><span>小型废钢3-1-4</span></li>
                                        <li><span>小型废钢3-1-5</span></li>
                                    </ul>
                                </li>
                                <li>
                                    <span>小型废钢3-2</span><i class="qrm-arrow-right"></i>
                                    <ul class="li-zi-3" style="display: none">
                                        <li><span>小型废钢3-2-1</span></li>
                                        <li><span>小型废钢3-2-2</span></li>
                                        <li><span>小型废钢3-2-3</span></li>
                                        <li><span>小型废钢3-2-4</span></li>
                                        <li><span>小型废钢3-2-5</span></li>
                                    </ul>
                                </li>
                                <li>
                                    <span>小型废钢3-3</span><i class="qrm-arrow-right"></i>
                                    <ul class="li-zi-3" style="display: none">
                                        <li><span>小型废钢3-3-1</span></li>
                                        <li><span>小型废钢3-3-2</span></li>
                                        <li><span>小型废钢3-3-3</span></li>
                                        <li><span>小型废钢3-3-4</span></li>
                                        <li><span>小型废钢3-3-5</span></li>
                                    </ul>
                                </li>
                                <li>
                                    <span>小型废钢3-4</span><i class="qrm-arrow-right"></i>
                                    <ul class="li-zi-3" style="display: none">
                                        <li><span>小型废钢3-4-1</span></li>
                                        <li><span>小型废钢3-4-2</span></li>
                                        <li><span>小型废钢3-4-3</span></li>
                                        <li><span>小型废钢3-4-4</span></li>
                                        <li><span>小型废钢3-4-5</span></li>
                                    </ul>
                                </li>
                                <li>
                                    <span>小型废钢3-5</span><i class="qrm-arrow-right"></i>
                                    <ul class="li-zi-3" style="display: none">
                                        <li><span>小型废钢3-5-1</span></li>
                                        <li><span>小型废钢3-5-2</span></li>
                                        <li><span>小型废钢3-5-3</span></li>
                                        <li><span>小型废钢3-5-4</span></li>
                                        <li><span>小型废钢3-5-5</span></li>
                                    </ul>
                                </li>
                            </ul>
                        </li>
                        <li>
                            <span>小型废钢4</span><i class="qrm-arrow-right"></i>
                            <ul class="li-zi-2" style="display: none">
                                <li>
                                    <span>小型废钢4-1</span><i class="qrm-arrow-right"></i>
                                    <ul class="li-zi-3" style="display: none">
                                        <li><span>小型废钢4-1-1</span></li>
                                        <li><span>小型废钢4-1-2</span></li>
                                        <li><span>小型废钢4-1-3</span></li>
                                        <li><span>小型废钢4-1-4</span></li>
                                        <li><span>小型废钢4-1-5</span></li>
                                    </ul>
                                </li>
                                <li>
                                    <span>小型废钢4-2</span><i class="qrm-arrow-right"></i>
                                    <ul class="li-zi-3" style="display: none">
                                        <li><span>小型废钢4-2-1</span></li>
                                        <li><span>小型废钢4-2-2</span></li>
                                        <li><span>小型废钢4-2-3</span></li>
                                        <li><span>小型废钢4-2-4</span></li>
                                        <li><span>小型废钢4-2-5</span></li>
                                    </ul>
                                </li>
                                <li>
                                    <span>小型废钢4-3</span><i class="qrm-arrow-right"></i>
                                    <ul class="li-zi-3" style="display: none">
                                        <li><span>小型废钢4-3-1</span></li>
                                        <li><span>小型废钢4-3-2</span></li>
                                        <li><span>小型废钢4-3-3</span></li>
                                        <li><span>小型废钢4-3-4</span></li>
                                        <li><span>小型废钢4-3-5</span></li>
                                    </ul>
                                </li>
                                <li>
                                    <span>小型废钢4-4</span><i class="qrm-arrow-right"></i>
                                    <ul class="li-zi-3" style="display: none">
                                        <li><span>小型废钢4-4-1</span></li>
                                        <li><span>小型废钢4-4-2</span></li>
                                        <li><span>小型废钢4-4-3</span></li>
                                        <li><span>小型废钢4-4-4</span></li>
                                        <li><span>小型废钢4-4-5</span></li>
                                    </ul>
                                </li>
                                <li>
                                    <span>小型废钢4-5</span><i class="qrm-arrow-right"></i>
                                    <ul class="li-zi-3" style="display: none">
                                        <li><span>小型废钢4-5-1</span></li>
                                        <li><span>小型废钢4-5-2</span></li>
                                        <li><span>小型废钢4-5-3</span></li>
                                        <li><span>小型废钢4-5-4</span></li>
                                        <li><span>小型废钢4-5-5</span></li>
                                    </ul>
                                </li>
                            </ul>
                        </li>
                        <li>
                            <span>小型废钢5</span><i class="qrm-arrow-right"></i>
                            <ul class="li-zi-2" style="display: none">
                                <li>
                                    <span>小型废钢5-1</span><i class="qrm-arrow-right"></i>
                                    <ul class="li-zi-3" style="display: none">
                                        <li><span>小型废钢5-1-1</span></li>
                                        <li><span>小型废钢5-1-2</span></li>
                                        <li><span>小型废钢5-1-3</span></li>
                                        <li><span>小型废钢5-1-4</span></li>
                                        <li><span>小型废钢5-1-5</span></li>
                                    </ul>
                                </li>
                                <li>
                                    <span>小型废钢5-2</span><i class="qrm-arrow-right"></i>
                                    <ul class="li-zi-3" style="display: none">
                                        <li><span>小型废钢5-2-1</span></li>
                                        <li><span>小型废钢5-2-2</span></li>
                                        <li><span>小型废钢5-2-3</span></li>
                                        <li><span>小型废钢5-2-4</span></li>
                                        <li><span>小型废钢5-2-5</span></li>
                                    </ul>
                                </li>
                                <li>
                                    <span>小型废钢5-3</span><i class="qrm-arrow-right"></i>
                                    <ul class="li-zi-3" style="display: none">
                                        <li><span>小型废钢5-3-1</span></li>
                                        <li><span>小型废钢5-3-2</span></li>
                                        <li><span>小型废钢5-3-3</span></li>
                                        <li><span>小型废钢5-3-4</span></li>
                                        <li><span>小型废钢5-3-5</span></li>
                                    </ul>
                                </li>
                                <li>
                                    <span>小型废钢5-4</span><i class="qrm-arrow-right"></i>
                                    <ul class="li-zi-3" style="display: none">
                                        <li><span>小型废钢5-4-1</span></li>
                                        <li><span>小型废钢5-4-2</span></li>
                                        <li><span>小型废钢5-4-3</span></li>
                                        <li><span>小型废钢5-4-4</span></li>
                                        <li><span>小型废钢5-4-5</span></li>
                                    </ul>
                                </li>
                                <li>
                                    <span>小型废钢5-5</span><i class="qrm-arrow-right"></i>
                                    <ul class="li-zi-3" style="display: none">
                                        <li><span>小型废钢5-5-1</span></li>
                                        <li><span>小型废钢5-5-2</span></li>
                                        <li><span>小型废钢5-5-3</span></li>
                                        <li><span>小型废钢5-5-4</span></li>
                                        <li><span>小型废钢5-5-5</span></li>
                                    </ul>
                                </li>
                            </ul>
                        </li>
                    </ul>
                </li>
                <!--轻薄-->
                <li>
                    <span>轻薄废钢</span><i class="qrm-arrow-right"></i>
                    <ul class="li-zi-1" style="display: none">
                        <li>
                            <span>轻薄废钢1</span><i class="qrm-arrow-right"></i>
                            <ul class="li-zi-2" style="display: none">
                                <li>
                                    <span>轻薄废钢1-1</span><i class="qrm-arrow-right"></i>
                                    <ul class="li-zi-3" style="display: none">
                                        <li><span>轻薄废钢1-1-1</span></li>
                                        <li><span>轻薄废钢1-1-2</span></li>
                                        <li><span>轻薄废钢1-1-3</span></li>
                                        <li><span>轻薄废钢1-1-4</span></li>
                                        <li><span>轻薄废钢1-1-5</span></li>
                                    </ul>
                                </li>
                                <li>
                                    <span>轻薄废钢1-2</span><i class="qrm-arrow-right"></i>
                                    <ul class="li-zi-3" style="display: none">
                                        <li><span>轻薄废钢1-2-1</span></li>
                                        <li><span>轻薄废钢1-2-2</span></li>
                                        <li><span>轻薄废钢1-2-3</span></li>
                                        <li><span>轻薄废钢1-2-4</span></li>
                                        <li><span>轻薄废钢1-2-5</span></li>
                                    </ul>
                                </li>
                                <li>
                                    <span>轻薄废钢1-3</span><i class="qrm-arrow-right"></i>
                                    <ul class="li-zi-3" style="display: none">
                                        <li><span>轻薄废钢1-3-1</span></li>
                                        <li><span>轻薄废钢1-3-2</span></li>
                                        <li><span>轻薄废钢1-3-3</span></li>
                                        <li><span>轻薄废钢1-3-4</span></li>
                                        <li><span>轻薄废钢1-3-5</span></li>
                                    </ul>
                                </li>
                                <li>
                                    <span>轻薄废钢1-4</span><i class="qrm-arrow-right"></i>
                                    <ul class="li-zi-3" style="display: none">
                                        <li><span>轻薄废钢1-4-1</span></li>
                                        <li><span>轻薄废钢1-4-2</span></li>
                                        <li><span>轻薄废钢1-4-3</span></li>
                                        <li><span>轻薄废钢1-4-4</span></li>
                                        <li><span>轻薄废钢1-4-5</span></li>
                                    </ul>
                                </li>
                                <li>
                                    <span>轻薄废钢1-5</span><i class="qrm-arrow-right"></i>
                                    <ul class="li-zi-3" style="display: none">
                                        <li><span>轻薄废钢1-5-1</span></li>
                                        <li><span>轻薄废钢1-5-2</span></li>
                                        <li><span>轻薄废钢1-5-3</span></li>
                                        <li><span>轻薄废钢1-5-4</span></li>
                                        <li><span>轻薄废钢1-5-5</span></li>
                                    </ul>
                                </li>
                            </ul>
                        </li>
                        <li>
                            <span>轻薄废钢2</span><i class="qrm-arrow-right"></i>
                            <ul class="li-zi-2" style="display: none">
                                <li>
                                    <span>轻薄废钢2-1</span><i class="qrm-arrow-right"></i>
                                    <ul class="li-zi-3" style="display: none">
                                        <li><span>轻薄废钢2-1-1</span></li>
                                        <li><span>轻薄废钢2-1-2</span></li>
                                        <li><span>轻薄废钢2-1-3</span></li>
                                        <li><span>轻薄废钢2-1-4</span></li>
                                        <li><span>轻薄废钢2-1-5</span></li>
                                    </ul>
                                </li>
                                <li>
                                    <span>轻薄废钢2-2</span><i class="qrm-arrow-right"></i>
                                    <ul class="li-zi-3" style="display: none">
                                        <li><span>轻薄废钢2-2-1</span></li>
                                        <li><span>轻薄废钢2-2-2</span></li>
                                        <li><span>轻薄废钢2-2-3</span></li>
                                        <li><span>轻薄废钢2-2-4</span></li>
                                        <li><span>轻薄废钢2-2-5</span></li>
                                    </ul>
                                </li>
                                <li>
                                    <span>轻薄废钢2-3</span><i class="qrm-arrow-right"></i>
                                    <ul class="li-zi-3" style="display: none">
                                        <li><span>轻薄废钢2-3-1</span></li>
                                        <li><span>轻薄废钢2-3-2</span></li>
                                        <li><span>轻薄废钢2-3-3</span></li>
                                        <li><span>轻薄废钢2-3-4</span></li>
                                        <li><span>轻薄废钢2-3-5</span></li>
                                    </ul>
                                </li>
                                <li>
                                    <span>轻薄废钢2-4</span><i class="qrm-arrow-right"></i>
                                    <ul class="li-zi-3" style="display: none">
                                        <li><span>轻薄废钢2-4-1</span></li>
                                        <li><span>轻薄废钢2-4-2</span></li>
                                        <li><span>轻薄废钢2-4-3</span></li>
                                        <li><span>轻薄废钢2-4-4</span></li>
                                        <li><span>轻薄废钢2-4-5</span></li>
                                    </ul>
                                </li>
                                <li>
                                    <span>轻薄废钢2-5</span><i class="qrm-arrow-right"></i>
                                    <ul class="li-zi-3" style="display: none">
                                        <li><span>轻薄废钢2-5-1</span></li>
                                        <li><span>轻薄废钢2-5-2</span></li>
                                        <li><span>轻薄废钢2-5-3</span></li>
                                        <li><span>轻薄废钢2-5-4</span></li>
                                        <li><span>轻薄废钢2-5-5</span></li>
                                    </ul>
                                </li>
                            </ul>
                        </li>
                        <li>
                            <span>轻薄废钢3</span><i class="qrm-arrow-right"></i>
                            <ul class="li-zi-2" style="display: none">
                                <li>
                                    <span>轻薄废钢3-1</span><i class="qrm-arrow-right"></i>
                                    <ul class="li-zi-3" style="display: none">
                                        <li><span>轻薄废钢3-1-1</span></li>
                                        <li><span>轻薄废钢3-1-2</span></li>
                                        <li><span>轻薄废钢3-1-3</span></li>
                                        <li><span>轻薄废钢3-1-4</span></li>
                                        <li><span>轻薄废钢3-1-5</span></li>
                                    </ul>
                                </li>
                                <li>
                                    <span>轻薄废钢3-2</span><i class="qrm-arrow-right"></i>
                                    <ul class="li-zi-3" style="display: none">
                                        <li><span>轻薄废钢3-2-1</span></li>
                                        <li><span>轻薄废钢3-2-2</span></li>
                                        <li><span>轻薄废钢3-2-3</span></li>
                                        <li><span>轻薄废钢3-2-4</span></li>
                                        <li><span>轻薄废钢3-2-5</span></li>
                                    </ul>
                                </li>
                                <li>
                                    <span>轻薄废钢3-3</span><i class="qrm-arrow-right"></i>
                                    <ul class="li-zi-3" style="display: none">
                                        <li><span>轻薄废钢3-3-1</span></li>
                                        <li><span>轻薄废钢3-3-2</span></li>
                                        <li><span>轻薄废钢3-3-3</span></li>
                                        <li><span>轻薄废钢3-3-4</span></li>
                                        <li><span>轻薄废钢3-3-5</span></li>
                                    </ul>
                                </li>
                                <li>
                                    <span>轻薄废钢3-4</span><i class="qrm-arrow-right"></i>
                                    <ul class="li-zi-3" style="display: none">
                                        <li><span>轻薄废钢3-4-1</span></li>
                                        <li><span>轻薄废钢3-4-2</span></li>
                                        <li><span>轻薄废钢3-4-3</span></li>
                                        <li><span>轻薄废钢3-4-4</span></li>
                                        <li><span>轻薄废钢3-4-5</span></li>
                                    </ul>
                                </li>
                                <li>
                                    <span>轻薄废钢3-5</span><i class="qrm-arrow-right"></i>
                                    <ul class="li-zi-3" style="display: none">
                                        <li><span>轻薄废钢3-5-1</span></li>
                                        <li><span>轻薄废钢3-5-2</span></li>
                                        <li><span>轻薄废钢3-5-3</span></li>
                                        <li><span>轻薄废钢3-5-4</span></li>
                                        <li><span>轻薄废钢3-5-5</span></li>
                                    </ul>
                                </li>
                            </ul>
                        </li>
                        <li>
                            <span>轻薄废钢4</span><i class="qrm-arrow-right"></i>
                            <ul class="li-zi-2" style="display: none">
                                <li>
                                    <span>轻薄废钢4-1</span><i class="qrm-arrow-right"></i>
                                    <ul class="li-zi-3" style="display: none">
                                        <li><span>轻薄废钢4-1-1</span></li>
                                        <li><span>轻薄废钢4-1-2</span></li>
                                        <li><span>轻薄废钢4-1-3</span></li>
                                        <li><span>轻薄废钢4-1-4</span></li>
                                        <li><span>轻薄废钢4-1-5</span></li>
                                    </ul>
                                </li>
                                <li>
                                    <span>轻薄废钢4-2</span><i class="qrm-arrow-right"></i>
                                    <ul class="li-zi-3" style="display: none">
                                        <li><span>轻薄废钢4-2-1</span></li>
                                        <li><span>轻薄废钢4-2-2</span></li>
                                        <li><span>轻薄废钢4-2-3</span></li>
                                        <li><span>轻薄废钢4-2-4</span></li>
                                        <li><span>轻薄废钢4-2-5</span></li>
                                    </ul>
                                </li>
                                <li>
                                    <span>轻薄废钢4-3</span><i class="qrm-arrow-right"></i>
                                    <ul class="li-zi-3" style="display: none">
                                        <li><span>轻薄废钢4-3-1</span></li>
                                        <li><span>轻薄废钢4-3-2</span></li>
                                        <li><span>轻薄废钢4-3-3</span></li>
                                        <li><span>轻薄废钢4-3-4</span></li>
                                        <li><span>轻薄废钢4-3-5</span></li>
                                    </ul>
                                </li>
                                <li>
                                    <span>轻薄废钢4-4</span><i class="qrm-arrow-right"></i>
                                    <ul class="li-zi-3" style="display: none">
                                        <li><span>轻薄废钢4-4-1</span></li>
                                        <li><span>轻薄废钢4-4-2</span></li>
                                        <li><span>轻薄废钢4-4-3</span></li>
                                        <li><span>轻薄废钢4-4-4</span></li>
                                        <li><span>轻薄废钢4-4-5</span></li>
                                    </ul>
                                </li>
                                <li>
                                    <span>轻薄废钢4-5</span><i class="qrm-arrow-right"></i>
                                    <ul class="li-zi-3" style="display: none">
                                        <li><span>轻薄废钢4-5-1</span></li>
                                        <li><span>轻薄废钢4-5-2</span></li>
                                        <li><span>轻薄废钢4-5-3</span></li>
                                        <li><span>轻薄废钢4-5-4</span></li>
                                        <li><span>轻薄废钢4-5-5</span></li>
                                    </ul>
                                </li>
                            </ul>
                        </li>
                        <li>
                            <span>轻薄废钢5</span><i class="qrm-arrow-right"></i>
                            <ul class="li-zi-2" style="display: none">
                                <li>
                                    <span>轻薄废钢5-1</span><i class="qrm-arrow-right"></i>
                                    <!--<ul class="li-zi-3" style="display: none">-->
                                    <!--<li><span>轻薄废钢5-1-1</span></li>-->
                                    <!--<li><span>轻薄废钢5-1-2</span></li>-->
                                    <!--<li><span>轻薄废钢5-1-3</span></li>-->
                                    <!--<li><span>轻薄废钢5-1-4</span></li>-->
                                    <!--<li><span>轻薄废钢5-1-5</span></li>-->
                                    <!--</ul>-->
                                </li>
                                <li>
                                    <span>轻薄废钢5-2</span><i class="qrm-arrow-right"></i>
                                    <!--<ul class="li-zi-3" style="display: none">-->
                                    <!--<li><span>轻薄废钢5-2-1</span></li>-->
                                    <!--<li><span>轻薄废钢5-2-2</span></li>-->
                                    <!--<li><span>轻薄废钢5-2-3</span></li>-->
                                    <!--<li><span>轻薄废钢5-2-4</span></li>-->
                                    <!--<li><span>轻薄废钢5-2-5</span></li>-->
                                    <!--</ul>-->
                                </li>
                                <li>
                                    <span>轻薄废钢5-3</span><i class="qrm-arrow-right"></i>
                                    <ul class="li-zi-3" style="display: none">
                                        <li><span>轻薄废钢5-3-1</span></li>
                                        <li><span>轻薄废钢5-3-2</span></li>
                                        <li><span>轻薄废钢5-3-3</span></li>
                                        <li><span>轻薄废钢5-3-4</span></li>
                                        <li><span>轻薄废钢5-3-5</span></li>
                                    </ul>
                                </li>
                                <li>
                                    <span>轻薄废钢5-4</span><i class="qrm-arrow-right"></i>
                                    <ul class="li-zi-3" style="display: none">
                                        <li><span>轻薄废钢5-4-1</span></li>
                                        <li><span>轻薄废钢5-4-2</span></li>
                                        <li><span>轻薄废钢5-4-3</span></li>
                                        <li><span>轻薄废钢5-4-4</span></li>
                                        <li><span>轻薄废钢5-4-5</span></li>
                                    </ul>
                                </li>
                                <li>
                                    <span>轻薄废钢5-5</span><i class="qrm-arrow-right"></i>
                                    <ul class="li-zi-3" style="display: none">
                                        <li><span>轻薄废钢5-5-1</span></li>
                                        <li><span>轻薄废钢5-5-2</span></li>
                                        <li><span>轻薄废钢5-5-3</span></li>
                                        <li><span>轻薄废钢5-5-4</span></li>
                                        <li><span>轻薄废钢5-5-5</span></li>
                                    </ul>
                                </li>
                            </ul>
                        </li>
                    </ul>
                </li>
            </ul>
            <p class="clearfix"></p>
        </div>
        <div class="qrm-border">
            <ul class="qrm-lev-2 qrm-lev">

            </ul>
            <p class="clearfix"></p>
        </div>
        <div class="qrm-border">
            <ul class="qrm-lev-3 qrm-lev">

            </ul>
            <p class="clearfix"></p>
        </div>
        <div class="qrm-border">
            <ul class="qrm-lev-4 qrm-lev">

            </ul>
            <p class="clearfix"></p>
        </div>
        <p class="clearfix"></p>
    </div>
    <p class="clearfix"></p>
</div>
<!--品名结束-->
</center>
<script src="js/jquery.min.js"></script>
<script src="js/qrm-pinming.js"></script>


</body>
</html>