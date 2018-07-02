ビルド方法
----------

以下手順を実行する::

    $ git clone git@github.com:pyconjp/kyushu-2018-after-report.git
    $ cd kyushu-2018-after-report
    $ python3 -m venv venv
    $ source venv/bin/activate
    (env)$ pip install -r requirements.txt
    (env)$ make html

レポート内容
----------

構成案::

    * (???)開催地と開催概要 source/about_the_event.rst
    * (???)Keynoteのトーク source/keynote_talk.rst
    * セション 
      * トラック1 
        (???)A-1: source/a-1.rst
        (???)A-2: source/a-2.rst
        (???)A-3: source/a-3.rst
        (???)A-4: source/a-4.rst
        (???)A-5: source/a-5.rst
        (???)A-6: source/a-6.rst
        (???)A-7: source/a-7.rst
      * トラック2
        (???)B-1: source/b-1.rst
        (???)B-2: source/b-2.rst
        (???)B-3: source/b-3.rst
        (???)B-4: source/b-4.rst
        (???)B-5: source/b-5.rst
        (???)B-6: source/b-6.rst
        (???)B-7: source/b-7.rst
    * 他の企画: 
      * (???)オープニング source/openning.rst
      * (???)Ask th speaker source/ask_the_speaker.rst
      * (???)ランチべ&スポンサーLT  source/lunch_and_lt.rst
      * (???)ジョブボード source/job_board.rst
      * (???)記念撮影 source/photo_session.rst
      * (???)クロージング source/closing.rst
      * (???)懇親会 source/social_gathering.rst
    * (???)PyCon Kyushuの実行委員の活動 source/pycon_kyushu_activity.rst
      * 次回の予定など
    * (???)PYCon Kyushu in Fukuoka 実行委員メンバー紹介 source/members.rst
    * (kiyota)最後に source/after_all.rst
      * コミュニティー活動を各地に広めること 
    * (kiyota)執筆者 source/authors.rst
