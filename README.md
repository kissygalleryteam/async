## 综述

async

## 初始化组件

    S.use('kg/async/0.9.0/index', function (S, async) {
            async.series([function (next) {
                console.log(+new Date());
                setTimeout(next, 1000);
            }, function (next) {
                console.log(+new Date());
                setTimeout(next, 1000);
            }], function () {
                console.log(+new Date());
            });
        });

## API说明

    https://github.com/caolan/async