## 目前，在GitHub上的这个testgit仓库还是空的，GitHub告诉我们，可以从这个仓库克隆出新的仓库，也可以把一个已有的本地仓库与之关联，然后，把本地仓库的内容推送到GitHub仓库。 NE1OLY

更新时间：2026-09-15 07:11:55.010

3ruir8.kvb1993.com
那么一般情况下，那些分支要推送呢？
3i38ks.cdroutlet.com
47de1p.ecvyksp.cn
可以看到 推送成功了，如果我们现在要推送到其他分支，比如dev分支上，我们还是那个命令 git push origin dev
4htljf.kvb1979.com
2ofdjj.hothairybushes.com
3yvtlh.kvb1998.com
2r4v8q.kvb1992.com
3ets5j.kvb1995.com
2wr0my.ecvyksp.cn
Git算不算程序员的必备技能？
3alj0r.kvb1991.com
331jsg.inmolopez.com
2zwzxp.ecvyksp.cn
2xlryu.kvb1999.com
我们可以看到如上，推送成功，我们可以继续来截图github上的readme.txt内容 如下：
32aw33.ecvyksp.cn
48xfab.hothairybushes.com
3n5259.kvb1982.com
3az1tb.ecvyksp.cn
32meo0.kvb1987.com
Git算不算程序员的必备技能？
49wprh.kvb1992.com
现在我想把本地更新的readme.txt代码推送到远程库中，使用命令如下：
2wkmvv.kvb1986.com
2t8apu.ecvyksp.cn
3589pn.kvb1995.com
48ga4q.cdroutlet.com
Git算不算程序员的必备技能？
43jj75.inmolopez.com
334dn1.inmolopez.com
49f47r.kvb1995.com
3qtne2.kvb1996.com
3n2av0.compasslandconsultants.com
3wfd4q.kvb1985.com
3r53jn.kvb1986.com
322dfs.kvb1997.com
本地的readme.txt代码如下：
4429w7.hoodamath2.com
Git算不算程序员的必备技能？
2qplui.hothairybushes.com
2zyqtr.kvb1987.com
31ts9g.hoodamath2.com
3wehqt.kvb1978.com
48bntv.misturabela.com
比如我现在的github上的readme.txt代码如下：
3zw9sl.kvb1978.com
30lynl.kvb1999.com
3gxwwo.hongyihualang.cn
38f75z.kvb1980.com
使用命令 git push origin master
39hs4i.inmolopez.com
3eg563.kvb1992.com
3r3rwu.ecvyksp.cn
41498o.kvb1985.com
推送分支就是把该分支上所有本地提交到远程库中，推送时，要指定本地分支，这样，Git就会把该分支推送到远程库对应的远程分支上：
3r8tan.misturabela.com
一：推送分支：
3rkf7i.kvb1993.com
Git算不算程序员的必备技能？
2ud0ti.ecvyksp.cn
如下演示：
4d55iz.kvb1982.com
要查看远程库的详细信息 使用 git remote –v
3kw3xc.ecvyksp.cn
2saxpg.misturabela.com
要查看远程库的信息 使用 git remote
2occhm.ecvyksp.cn
3kby63.kvb1988.com
439b3x.hoodamath2.com
当你从远程库克隆时候，实际上Git自动把本地的master分支和远程的master分支对应起来了，并且远程库的默认名称是origin。
2yc04j.hongyihualang.cn
3otapw.misturabela.com
47ikge.misturabela.com
3td1dg.kvb1998.com
3cvssu.kvb1992.com
3y05bx.hongyihualang.cn
3mj9u6.hongyihualang.cn
38pcvr.hothairybushes.com
八：多人协作。
37jd77.ecvyksp.cn
Git算不算程序员的必备技能？
3lrnm9.kvb1999.com
演示如下
3web1x.hoodamath2.com
3nb8u5.kvb1980.com
2.另一种方式是使用git stash pop,恢复的同时把stash内容也删除了。
46o7ye.kvb1993.com
1.git stash apply恢复，恢复后，stash内容并不删除，你需要使用命令git stash drop来删除。
3fh0um.kvb1983.com
46dpd2.kvb1988.com
2yqfnp.kvb1997.com
2xgh1c.kvb1988.com
2utn88.kvb1998.com
工作现场还在，Git把stash内容存在某个地方了，但是需要恢复一下，可以使用如下2个方法：
32asj5.hothairybushes.com
Git算不算程序员的必备技能？
35tkgg.kvb1980.com
46s142.kvb1997.com
工作区是干净的，那么我们工作现场去哪里呢？我们可以使用命令 git stash list来查看下。如下：
35252s.compasslandconsultants.com
2zpfx5.cdroutlet.com
Git算不算程序员的必备技能？
3w1v9w.kvb1987.com
4goyt2.kvb1995.com
3fvplk.cdroutlet.com
现在，我们回到dev分支上干活了。
2qtc3q.kvb1983.com
36aot1.inmolopez.com
Git算不算程序员的必备技能？
3zxpmk.hothairybushes.com
修复完成后，切换到master分支上，并完成合并，最后删除issue-404分支。演示如下：
3v08rf.hoodamath2.com
3m1tgt.misturabela.com
3k0w1k.ecvyksp.cn
4if0pp.kvb1993.com
4j4e00.kvb1991.com
40mpbn.kvb1992.com
3qi5vl.kvb1998.com
2z025c.inmolopez.com
Git算不算程序员的必备技能？
338oak.kvb1983.com
3v86xe.hothairybushes.com
2ys141.kvb1979.com
首先我们要确定在那个分支上修复bug，比如我现在是在主分支master上来修复的，现在我要在master分支上创建一个临时分支，演示如下：
2lclry.ecvyksp.cn
所以现在我可以通过创建issue-404分支来修复bug了。
4a7tcd.kvb1999.com
380dx2.compasslandconsultants.com
3af2dh.ecvyksp.cn
3wk7yr.compasslandconsultants.com
4dcuwb.kvb1983.com
3nxkv5.hothairybushes.com
Git算不算程序员的必备技能？
2menv4.ecvyksp.cn
2z1dd4.compasslandconsultants.com
并不是我不想提交，而是工作进行到一半时候，我们还无法提交，比如我这个分支bug要2天完成，但是我issue-404 bug需要5个小时内完成。怎么办呢？还好，Git还提供了一个stash功能，可以把当前工作现场 ”隐藏起来”，等以后恢复现场后继续工作。如下：
3k81iu.ecvyksp.cn
3fe6ql.kvb1993.com
Git算不算程序员的必备技能？
461xzn.cdroutlet.com
3yft0f.kvb1998.com
2nm7uq.compasslandconsultants.com
比如我在开发中接到一个404 bug时候，我们可以创建一个404分支来修复它，但是，当前的dev分支上的工作还没有提交。比如如下：
2vy7lq.kvb1978.com
4f0xj5.kvb1993.com
2zyxsd.kvb1980.com
3pgwm1.kvb1999.com
36bqsy.inmolopez.com
3wc7l6.compasslandconsultants.com
在开发中，会经常碰到bug问题，那么有了bug就需要修复，在Git中，分支是很强大的，每个bug都可以通过一个临时分支来修复，修复完成后，合并分支，然后将临时的分支删除掉。
2zp2mr.hongyihualang.cn
七：bug分支：
48s5ik.compasslandconsultants.com
分支策略：首先master主分支应该是非常稳定的，也就是用来发布新版本，一般情况下不允许在上面干活，干活一般情况下在新建的dev分支上干活，干完后，比如上要发布，或者说dev分支代码稳定后可以合并到主分支master上来。
3pgrgm.kvb1990.com
Git算不算程序员的必备技能？
461m3b.kvb1989.com
47cdqj.inmolopez.com
2nudsg.cdroutlet.com
创建一个dev分支。 修改readme.txt内容。 添加到暂存区。 切换回主分支(master)。 合并dev分支，使用命令 git merge –no-ff -m “注释” dev 查看历史记录 截图如下：
3pfr9b.kvb1986.com
通常合并分支时，git一般使用”Fast forward”模式，在这种模式下，删除分支后，会丢掉分支信息，现在我们来使用带参数 –no-ff来禁用”Fast forward”模式。首先我们来做demo演示下：
330bnt.kvb1986.com
3ppl2i.hoodamath2.com
3.分支管理策略。
30lhg0.kvb1983.com
Git算不算程序员的必备技能？
47ls16.misturabela.com
36ijtu.inmolopez.com
2sq00r.hongyihualang.cn
4gxi0j.kvb1987.com
3no707.kvb1987.com
2xsn6y.hongyihualang.cn
31gmg6.kvb1993.com
384a2a.hoodamath2.com
3g2wub.kvb1985.com
3d7f66.kvb1988.com
3gr42d.kvb1978.com
如果我想查看分支合并的情况的话，需要使用命令 git log.命令行演示如下：
3lr1td.cdroutlet.com
3hhlyv.cdroutlet.com
Git算不算程序员的必备技能？
32ilec.misturabela.com
4in480.kvb1992.com
385r9t.misturabela.com
3wgkrq.kvb1980.com
Git用，=======，标记出不同分支的内容，其中HEAD是指主分支修改的内容，fenzhi1 是指fenzhi1上修改的内容，我们可以修改下如下后保存：
4av287.kvb1995.com
3ruujw.kvb1983.com
39qc8d.hothairybushes.com
Git算不算程序员的必备技能？
316bqg.kvb1982.com
394dua.hongyihualang.cn
3qxllu.kvb1996.com
3z6xdq.kvb1988.com
3mwjv6.hoodamath2.com
3gkasu.misturabela.com
4fzx88.kvb1993.com
3hypx6.inmolopez.com
现在我们需要在master分支上来合并fenzhi1，如下操作：
2m608x.cdroutlet.com
37ej3m.misturabela.com
341kfi.hothairybushes.com
Git算不算程序员的必备技能？
3mty3z.kvb1981.com
同样，我们现在切换到master分支上来，也在最后一行添加内容，内容为99999999，如下所示：
35g8pw.cdroutlet.com
31mfsf.compasslandconsultants.com
Git算不算程序员的必备技能？
3yp9me.kvb1991.com
40n1d2.misturabela.com
2zcfh0.kvb1998.com
44r0w4.ecvyksp.cn
下面我们还是一步一步来，先新建一个新分支，比如名字叫fenzhi1，在readme.txt添加一行内容8888888，然后提交，如下所示：
312h8y.hoodamath2.com
如何解决冲突？
40l8y7.hoodamath2.com
3qh4j1.cdroutlet.com
3ktr4b.kvb1992.com
删除分支：git branch –d name
3q2fkg.ecvyksp.cn
33jcf9.kvb1978.com
35e7uj.cdroutlet.com
3f58b0.hongyihualang.cn
合并某分支到当前分支：git merge name
3z46kb.kvb1987.com
创建+切换分支：git checkout –b name
3af107.cdroutlet.com
3uulzk.misturabela.com
4d4ht5.kvb1981.com
37nveg.ecvyksp.cn
3fh0fr.kvb1985.com
2mk4fi.cdroutlet.com
3rwh62.hothairybushes.com
2za2qs.misturabela.com
切换分支：git checkout name
3gq3u0.hothairybushes.com
3kwimx.kvb1985.com
创建分支：git branch name
2v1kci.hongyihualang.cn
3q8nsi.kvb1996.com
查看分支：git branch
3axwoe.kvb1999.com
4gl8q9.kvb1999.com
总结创建与合并分支命令如下：
2rpxpp.inmolopez.com
3hri1p.compasslandconsultants.com
Git算不算程序员的必备技能？
3321s1.kvb1993.com
2wil95.hongyihualang.cn
3damms.kvb1992.com
3wph2j.kvb1993.com
44kdgq.hoodamath2.com
合并完成后，我们可以接着删除dev分支了，操作如下：
46gqkb.hongyihualang.cn
3e61fs.kvb1989.com
注意到上面的Fast-forward信息，Git告诉我们，这次合并是“快进模式”，也就是直接把master指向dev的当前提交，所以合并速度非常快。
2yp9i4.hothairybushes.com
2s1phf.ecvyksp.cn
349e3r.misturabela.com
git merge命令用于合并指定分支到当前分支上，合并后，再查看readme.txt内容，可以看到，和dev分支最新提交的是完全一样的。
3i6z16.ecvyksp.cn
Git算不算程序员的必备技能？
3npcei.kvb1997.com
2uksac.ecvyksp.cn
现在我们可以把dev分支上的内容合并到分支master上了，可以在master分支上，使用如下命令 git merge dev 如下所示：
3sc2n3.hoodamath2.com
Git算不算程序员的必备技能？
4bfdnb.kvb1996.com
3sh38c.kvb1981.com
3qh2mo.misturabela.com
3q9q7x.kvb1979.com
4fw6wm.kvb1999.com
现在dev分支工作已完成，现在我们切换到主分支master上，继续查看readme.txt内容如下：
3i4czb.misturabela.com
35ulv0.ecvyksp.cn
41ohmz.cdroutlet.com
4e1pwv.kvb1980.com
Git算不算程序员的必备技能？
4iizgo.kvb1995.com
32m78p.kvb1989.com
440oik.ecvyksp.cn
3kvf6o.hongyihualang.cn
2ol4f0.hothairybushes.com
3yv2wy.inmolopez.com
2unol6.kvb1988.com
首先我们先来查看下readme.txt内容，接着添加内容77777777，如下：
3go3vb.kvb1986.com
3rjjjx.kvb1978.com
git branch查看分支，会列出所有的分支，当前分支前面会添加一个星号。然后我们在dev分支上继续做demo，比如我们现在在readme.txt再增加一行 7777777777777
3kyhj8.inmolopez.com
2th3i9.compasslandconsultants.com
git checkout dev
3pmmbj.kvb1999.com
3q33zr.kvb1980.com
35yhca.kvb1993.com
3i8uw8.kvb1980.com
3b2t0d.kvb1983.com
git branch dev
48s07l.hothairybushes.com
3d1bf5.hoodamath2.com
46e6hf.compasslandconsultants.com
42bmrh.kvb1996.com
git checkout 命令加上 –b参数表示创建并切换，相当于如下2条命令
2yyten.hothairybushes.com
Git算不算程序员的必备技能？
2p913h.inmolopez.com
首先，我们来创建dev分支，然后切换到dev分支上。如下操作：
38h2a3.cdroutlet.com
在 版本回填退里，你已经知道，每次提交，Git都把它们串成一条时间线，这条时间线就是一个分支。截止到目前，只有一条时间线，在Git里，这个分支叫主分支，即master分支。HEAD严格来说不是指向提交，而是指向master，master才是指向提交的，所以，HEAD指向的就是当前分支。
2tao88.compasslandconsultants.com
4gaav5.kvb1980.com
3d0ie0.cdroutlet.com
3yf0cn.kvb1987.com
371sr2.kvb1998.com
2ywqsn.compasslandconsultants.com
3bed7f.kvb1998.com
400vwx.kvb1990.com
3y77ue.hoodamath2.com
六：创建与合并分支。
3dkoln.inmolopez.com
Git算不算程序员的必备技能？
3e4jhj.misturabela.com
3v3mi3.ecvyksp.cn
3l4e2w.inmolopez.com
2x8xky.kvb1981.com
3hqiib.compasslandconsultants.com
3wh4cj.misturabela.com
3qtue7.hongyihualang.cn
3f8z88.kvb1995.com
3kwyys.hongyihualang.cn
3tqzbf.inmolopez.com
3qsc7p.hothairybushes.com
3h8wbs.ecvyksp.cn
47u1mf.ecvyksp.cn
接着在我本地目录下 生成testgit2目录了，如下所示：
3fnqlr.hongyihualang.cn
3ax8j6.kvb1990.com
Git算不算程序员的必备技能？
3krlkz.ecvyksp.cn
3irbrd.kvb1988.com
现在，远程库已经准备好了，下一步是使用命令git clone克隆一个本地库了。如下所示：
3tm5hq.kvb1993.com
39wx16.hothairybushes.com
47359z.misturabela.com
46qzi1.kvb1980.com
4fc05a.kvb1989.com
Git算不算程序员的必备技能？
3h1tdy.ecvyksp.cn
47jzgn.misturabela.com
如下，我们看到：
3wrvmm.kvb1988.com
32gupu.hoodamath2.com
Git算不算程序员的必备技能？
3rjuhv.kvb1978.com
3edzlf.inmolopez.com
2r9foo.kvb1983.com
3abq1n.kvb1979.com
首先，登录github，创建一个新的仓库，名字叫testgit2.如下：
386hbq.kvb1979.com
2x4han.inmolopez.com
4ilmi2.kvb1996.com
现在我们想，假如远程库有新的内容了，我想克隆到本地来 如何克隆呢？
2wn5ed.inmolopez.com
如何从远程库克隆？上面我们了解了先有本地库，后有远程库时候，如何关联远程库。
2r6kza.hongyihualang.cn
把本地master分支的最新修改推送到github上了，现在你就拥有了真正的分布式版本库了。
3f2cvi.compasslandconsultants.com
3hfqaa.ecvyksp.cn
3jqeuc.inmolopez.com
35wbiz.kvb1979.com
git push origin master
2pjsx9.cdroutlet.com
49rvo8.kvb1997.com
3w3deb.kvb1988.com
3gbut9.hoodamath2.com
从现在起，只要本地作了提交，就可以通过如下命令：
36n68c.ecvyksp.cn
Git算不算程序员的必备技能？
3duuqw.kvb1991.com
30ectb.kvb1979.com
402e68.inmolopez.com
2z3emb.cdroutlet.com
42dxpo.cdroutlet.com
由于远程库是空的，我们第一次推送master分支时，加上了 –u参数，Git不但会把本地的master分支内容推送的远程新的master分支，还会把本地的master分支和远程的master分支关联起来，在以后的推送或者拉取时就可以简化命令。推送成功后，可以立刻在github页面中看到远程库的内容已经和本地一模一样了，上面的要输入github的用户名和密码如下所示：
3kvlri.kvb1996.com
把本地库的内容推送到远程，使用 git push命令，实际上是把当前分支master推送到远程。
2mnq6o.hoodamath2.com
Git算不算程序员的必备技能？
3eh4ko.inmolopez.com
356b57.hothairybushes.com
所有的如下：
2zvm1a.kvb1993.com
git remote add origin
4dpnbi.kvb1999.com
3stbpb.hongyihualang.cn
3hbbxt.hoodamath2.com
现在，我们根据GitHub的提示，在本地的testgit仓库下运行命令：

---

# 1y4tg6oh
Auto-created repository for publishing - 2026-09-15T07:11:48.617Z
