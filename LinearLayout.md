## LinearLayout のまとめ

```
 <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:orientation="horizontal" > //**LinearLayout縦一列なのを、ボタンなどを横一列にしてくれる** //

        <Button
            android:id="@+id/button"
            android:layout_width="0dp" // **横幅の間隔を均等に開けてくれるプロパティ layout_width=”0dp”を指定**//
            android:layout_height="wrap_content"
            android:layout_weight="1" // **ボタンを等幅に並べたい時は、ボタンにlayout_weight=”1″を指定** //
            android:text="Button" />

        <Button
            android:id="@+id/button2"
            android:layout_width="0dp"
            android:layout_height="wrap_content"
            android:layout_weight="1" // ボタンを等幅に並べたい時は、ボタンにlayout_weight=”1″を指定 //
            android:text="Button" />
    </LinearLayout>
 ```
