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
      * トラック2
        (???)B-5: source/b-5.rst
    * イベントサマリー: source/events_summary.rst
    * (???)PyCon Kyushuの実行委員の活動 source/pycon_kyushu_activity.rst
      * 次回の予定など
    * (???)PYCon Kyushu in Fukuoka 実行委員メンバー紹介 source/members.rst
    * (kiyota)最後に source/after_all.rst
      * コミュニティー活動を各地に広めること 
    * (kiyota)執筆者 source/authors.rst
