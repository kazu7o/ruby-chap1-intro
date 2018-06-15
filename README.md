# テクノロジー（藤原） 授業 6/8

今日の授業で打ったコマンドをコピー＆ペーストしてください。

（`irb`や`ruby`の実行結果も含めて全てをコピーしてください）

## ターミナルに打ったコマンド

```
kztmr@LaitFraise:~/fujiwara/ruby-chap1-intro % ruby helloruby.rb (git)-[master]
Hello, Ruby.
kztmr@LaitFraise:~/fujiwara/ruby-chap1-intro % irb               (git)-[master]
irb(main):001:0> print("Hello, Ruby.\n")
Hello, Ruby.
=> nil
irb(main):002:0> exit
kztmr@LaitFraise:~/fujiwara/ruby-chap1-intro % ruby helloruby.rb (git)-[master]
Hello,
Ruby
!
kztmr@LaitFraise:~/fujiwara/ruby-chap1-intro % ruby helloruby.rb (git)-[master]
Hello, "Ruby".
kztmr@LaitFraise:~/fujiwara/ruby-chap1-intro % ruby helloruby.rb (git)-[master]
Hello, \ Ruby.
kztmr@LaitFraise:~/fujiwara/ruby-chap1-intro % ruby helloruby.rb (git)-[master]
Hello, Ruby.
kztmr@LaitFraise:~/fujiwara/ruby-chap1-intro % ruby helloruby.rb (git)-[master]
Hello, Ruby!
kztmr@LaitFraise:~/fujiwara/ruby-chap1-intro % irb               (git)-[master]
irb(main):001:0> puts("Hello, Ruby.")
Hello, Ruby.
=> nil
irb(main):002:0> puts("Hello, ", "Ruby!")
Hello,
Ruby!
=> nil
irb(main):003:0> exit
kztmr@LaitFraise:~/fujiwara/ruby-chap1-intro % ruby puts_and_p.rb
Hello,
	Ruby.
"Hello,\n\tRuby."
kztmr@LaitFraise:~/fujiwara/ruby-chap1-intro %                   (git)-[master]

```

```
6/15
kztmr@LaitFraise:~/fujiwara/ruby-chap1-intro % ruby kiritsubo.rb (git)-[master]
いづれの御時にか女御更衣あまたさぶらいたまいけるなかい
いとやむごとなき際にはあらぬがすぐれて時めきたまふありけり
kztmr@LaitFraise:~/fujiwara/ruby-chap1-intro % irb --simple-prompt
>> 1
=> 1
>> 1.class
=> Integer
>> 3.1415
=> 3.1415
>> (3.1415).class
=> Float
>> exit()
kztmr@LaitFraise:~/fujiwara/ruby-chap1-intro % ruby area_volume.rb
表面積=2200
体積=6000
kztmr@LaitFraise:~/fujiwara/ruby-chap1-intro % irb --simple-prompt
>> 10.times do
?> print "Hello, Ruby.\n"
>> end
Hello, Ruby.
Hello, Ruby.
Hello, Ruby.
Hello, Ruby.
Hello, Ruby.
Hello, Ruby.
Hello, Ruby.
Hello, Ruby.
Hello, Ruby.
Hello, Ruby.
=> 10
>> quit
kztmr@LaitFraise:~/fujiwara/ruby-chap1-intro %                   (git)-[master]

```
