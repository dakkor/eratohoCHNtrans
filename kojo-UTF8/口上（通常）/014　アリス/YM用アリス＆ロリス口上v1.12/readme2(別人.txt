調教開始時に用意された口上のうち死にルート化していた箇所があったため修正
(IF RAND:2のみになっていた箇所をIF RAND:2 == 0にすることでルートとして通るように修正)
ELSEやENDIFの直後に挿入されていた不要な空白文字やタブ文字を削除、動作確認済み

修正しといたんで口上まとめに組み込んどいて下さい
このReadmeは消しといても結構です