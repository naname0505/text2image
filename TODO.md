'''
$ python
>>> import theano
>>> theano.version.full_version
'''

* L99のx = T.Matrix() の部分が一番の原因っぽい

* ~/.theanorc でfloat64をcastしているときにエラーを発生させるオプションを付加している。

* フォーク前のディレクトリとは/dataと/modelsの構成が違うので、実行コマンドのmodels/,,, => ../models/,,,  に変更する必要があるよ
