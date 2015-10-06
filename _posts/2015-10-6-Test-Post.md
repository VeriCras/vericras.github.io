---
layout: post
title: 테스트용 포스트!
---

test입니다

```html
    <h4 class="txt-sub-title">
        <span class="txt">입금계좌 안내</span>
    </h4>
    <table cellpadding="0" cellspacing="0" class="frm-column-tb">
        <colgroup>
            <col width="100">
            <col>
        </colgroup>
        <tbody>
            <tr>
                <th><div>입금계좌</div></th>
                <td><div class="fw-b">
                    [<?=$orderRow->LGD_FINANCENAME;?>]
                    <?=$orderRow->LGD_ACCOUNTNUM;?> /
                    <?=$orderRow->LGD_SAOWNER;?>
                </div></td>
            </tr>
            <tr>
                <th><div>입금자명</div></th>
                <td><div>
                    <?=$orderRow->LGD_PAYER;?>
                </div></td>
            </tr>
            <tr>
                <th><div>입금금액</div></th>
                <td><div class="cl-d-pink">
                    <?=number_format($orderRow->LGD_AMOUNT);?>원
                </div></td>
            </tr>
        </tbody>
    </table>
```
