<?xml version="1.0" encoding="utf-8"?>
<androidx.constraintlayout.widget.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:id="@+id/Constraintlayout"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:elevation="10dp"
    tools:context=".fragment.HomeFragment">

    <ScrollView
        android:id="@+id/scrollView2"
        android:layout_width="0dp"
        android:layout_height="0dp"
        android:layout_marginStart="1dp"
        android:layout_marginTop="1dp"
        android:layout_marginEnd="1dp"
        android:layout_marginBottom="1dp"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent">

        <LinearLayout
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:orientation="vertical">

            <ImageView
                android:id="@+id/logo"
                android:layout_width="125dp"
                android:layout_height="wrap_content"
                android:layout_marginLeft="20dp"
                android:layout_marginTop="30dp"
                android:layout_marginBottom="20dp"
                app:srcCompat="@drawable/logo" />

            <androidx.cardview.widget.CardView
                android:layout_width="match_parent"
                android:layout_height="match_parent"
                android:layout_marginLeft="20dp"
                android:layout_marginRight="20dp"
                android:layout_marginBottom="10dp"
                app:cardCornerRadius="10dp"
                app:cardElevation="0dp"
                app:cardMaxElevation="0dp"
                app:cardPreventCornerOverlap="false">

                <SearchView
                    android:id="@+id/search"
                    android:layout_width="match_parent"
                    android:layout_height="match_parent"
                    android:background="#ECECEC">

                </SearchView>
            </androidx.cardview.widget.CardView>

            <TextView
                android:id="@+id/tvHashtag"
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:layout_marginLeft="20dp"
                android:text="@string/titHash" />

            <LinearLayout
                android:id="@+id/hashtag"
                android:layout_width="match_parent"
                android:layout_height="match_parent"
                android:layout_marginLeft="20dp"
                android:layout_marginTop="5dp"
                android:layout_marginRight="20dp"
                android:orientation="horizontal">

                <Button
                    android:id="@+id/hashtag01"
                    android:layout_width="80dp"
                    android:layout_height="40dp"
                    android:layout_marginRight="8dp"
                    android:layout_weight="1"
                    android:backgroundTint="@color/main"
                    android:text="Button"
                    android:textColor="@color/text"
                    app:cornerRadius="5dp" />

                <Button
                    android:id="@+id/hashtag02"
                    android:layout_width="80dp"
                    android:layout_height="40dp"
                    android:layout_marginRight="8dp"
                    android:layout_weight="1"
                    android:backgroundTint="@color/main"
                    android:text="Button"
                    android:textColor="@color/text"
                    app:cornerRadius="5dp" />

                <Button
                    android:id="@+id/hashtag03"
                    android:layout_width="80dp"
                    android:layout_height="40dp"
                    android:layout_marginRight="8dp"
                    android:layout_weight="1"
                    android:backgroundTint="@color/main"
                    android:text="Button"
                    android:textColor="@color/text"
                    app:cornerRadius="5dp" />

                <Button
                    android:id="@+id/hashtag04"
                    android:layout_width="80dp"
                    android:layout_height="40dp"
                    android:layout_marginRight="8dp"
                    android:layout_weight="1"
                    android:backgroundTint="@color/main"
                    android:text="Button"
                    android:textColor="@color/text"
                    app:cornerRadius="5dp" />

            </LinearLayout>

            <androidx.cardview.widget.CardView
                android:id="@+id/memberInfo"
                android:layout_width="match_parent"
                android:layout_height="match_parent"
                android:layout_marginLeft="15dp"
                android:layout_marginTop="8dp"
                android:layout_marginRight="15dp"
                android:layout_marginBottom="8dp"
                android:layout_weight="1"
                app:cardBackgroundColor="@color/main"
                app:cardCornerRadius="10dp"
                app:cardUseCompatPadding="true">

                <LinearLayout
                    android:layout_width="wrap_content"
                    android:layout_height="match_parent"
                    android:orientation="horizontal">

                    <ImageView
                        android:id="@+id/imageView9"
                        android:layout_width="70dp"
                        android:layout_height="70dp"
                        android:layout_marginLeft="10dp"
                        android:layout_marginTop="8dp"
                        app:srcCompat="@drawable/user" />

                    <LinearLayout
                        android:layout_width="wrap_content"
                        android:layout_height="wrap_content"
                        android:layout_weight="1"
                        android:orientation="vertical">

                        <TextView
                            android:id="@+id/memberId"
                            android:layout_width="match_parent"
                            android:layout_height="wrap_content"
                            android:layout_marginTop="15dp"
                            android:text="@string/tvLogin" />

                        <TextView
                            android:id="@+id/memberContent"
                            android:layout_width="170dp"
                            android:layout_height="wrap_content"
                            android:layout_marginTop="5dp"
                            android:layout_marginBottom="20dp"
                            android:text="@string/tvLogintext"
                            android:textSize="12sp" />
                    </LinearLayout>

                </LinearLayout>

                <androidx.cardview.widget.CardView
                    android:id="@+id/pointInfo"
                    android:layout_width="70dp"
                    android:layout_height="70dp"
                    android:layout_gravity="right"
                    android:layout_marginTop="12dp"
                    android:layout_marginRight="20dp"
                    android:layout_weight="1"
                    app:cardBackgroundColor="#FFFFFF"
                    app:cardCornerRadius="200dp"
                    app:cardElevation="0dp"
                    app:cardMaxElevation="0dp">

                    <TextView
                        android:id="@+id/numPoint"
                        android:layout_width="match_parent"
                        android:layout_height="wrap_content"
                        android:layout_marginTop="15dp"
                        android:gravity="center"
                        android:text="10" />

                    <TextView
                        android:id="@+id/namePoint"
                        android:layout_width="match_parent"
                        android:layout_height="match_parent"
                        android:layout_marginTop="15dp"
                        android:gravity="center"
                        android:text="포인트" />

                </androidx.cardview.widget.CardView>

            </androidx.cardview.widget.CardView>

            <LinearLayout
                android:layout_width="match_parent"
                android:layout_height="match_parent"
                android:gravity="center"
                android:orientation="horizontal">

                <androidx.cardview.widget.CardView
                    android:id="@+id/checkBtn"
                    android:layout_width="185dp"
                    android:layout_height="185dp"
                    android:layout_marginRight="10dp"
                    app:cardBackgroundColor="@color/checkColor"
                    app:cardCornerRadius="10dp"
                    app:cardElevation="5dp"
                    app:cardPreventCornerOverlap="false"
                    app:cardUseCompatPadding="true">

                    <LinearLayout
                        android:layout_width="match_parent"
                        android:layout_height="match_parent"
                        android:orientation="vertical">

                        <ImageView
                            android:id="@+id/imageView2"
                            android:layout_width="90dp"
                            android:layout_height="90dp"
                            android:layout_gravity="center"
                            android:layout_marginLeft="5dp"
                            android:layout_marginTop="20dp"
                            app:srcCompat="@drawable/check" />

                        <TextView
                            android:id="@+id/textView3"
                            android:layout_width="100dp"
                            android:layout_height="wrap_content"
                            android:layout_gravity="center"
                            android:layout_marginTop="5dp"
                            android:gravity="center"
                            android:text="@string/tvCheck"
                            android:textColor="#FFFFFF" />

                    </LinearLayout>

                </androidx.cardview.widget.CardView>

                <androidx.cardview.widget.CardView
                    android:id="@+id/rankBtn"
                    android:layout_width="185dp"
                    android:layout_height="185dp"
                    android:background="#FFFFFF"
                    app:cardBackgroundColor="#FFFFFF"
                    app:cardCornerRadius="10dp"
                    app:cardElevation="5dp"
                    app:cardPreventCornerOverlap="false"
                    app:cardUseCompatPadding="true"
                    tools:layout_marginLeft="0dp">

                    <LinearLayout
                        android:layout_width="match_parent"
                        android:layout_height="match_parent"
                        android:orientation="vertical">

                        <ImageView
                            android:id="@+id/joinHome"
                            android:layout_width="90dp"
                            android:layout_height="90dp"
                            android:layout_gravity="center"
                            android:layout_marginTop="15dp"
                            app:srcCompat="@drawable/map" />

                        <TextView
                            android:id="@+id/textView2"
                            android:layout_width="100dp"
                            android:layout_height="wrap_content"
                            android:layout_gravity="center"
                            android:layout_marginTop="10dp"
                            android:gravity="center"
                            android:text="@string/tvRank"
                            android:textColor="@color/text" />
                    </LinearLayout>

                </androidx.cardview.widget.CardView>

            </LinearLayout>

            <TextView
                android:id="@+id/textView7"
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:layout_marginLeft="20dp"
                android:layout_marginTop="15dp"
                android:layout_marginBottom="6dp"
                android:text="@string/titCategory" />

            <LinearLayout
                android:layout_width="match_parent"
                android:layout_height="match_parent"
                android:orientation="horizontal">

                <androidx.recyclerview.widget.RecyclerView
                    android:id="@+id/categoryList"
                    android:layout_width="match_parent"
                    android:layout_height="match_parent"
                    android:layout_weight="1"
                    android:orientation="horizontal"
                    android:paddingLeft="20dp" />

            </LinearLayout>

            <androidx.cardview.widget.CardView
                android:id="@+id/quizBtn"
                android:layout_width="match_parent"
                android:layout_height="55dp"
                android:layout_marginLeft="20dp"
                android:layout_marginTop="20dp"
                android:layout_marginRight="20dp"
                android:layout_marginBottom="15dp"
                app:cardBackgroundColor="@color/subYellow"
                app:cardCornerRadius="8dp"
                app:cardElevation="0dp">

                <LinearLayout
                    android:layout_width="match_parent"
                    android:layout_height="match_parent"
                    android:orientation="horizontal">

                    <ImageView
                        android:id="@+id/imageView15"
                        android:layout_width="0dp"
                        android:layout_height="40dp"
                        android:layout_gravity="center"
                        android:layout_marginLeft="20dp"
                        android:layout_weight="1"
                        app:srcCompat="@drawable/quiz" />

                    <TextView
                        android:id="@+id/textView6"
                        android:layout_width="140dp"
                        android:layout_height="match_parent"
                        android:layout_marginLeft="10dp"
                        android:layout_weight="1"
                        android:gravity="center_vertical"
                        android:text="@string/tvQuiz" />

                    <ImageView
                        android:id="@+id/imageView11"
                        android:layout_width="wrap_content"
                        android:layout_height="match_parent"
                        android:layout_weight="1"
                        android:padding="10dp"
                        app:srcCompat="@drawable/right" />
                </LinearLayout>
            </androidx.cardview.widget.CardView>

            <androidx.cardview.widget.CardView
                android:id="@+id/calBtn"
                android:layout_width="match_parent"
                android:layout_height="55dp"
                android:layout_marginLeft="20dp"
                android:layout_marginRight="20dp"
                android:layout_marginBottom="20dp"
                app:cardBackgroundColor="@color/subBlue"
                app:cardCornerRadius="8dp"
                app:cardElevation="0dp">

                <LinearLayout
                    android:layout_width="match_parent"
                    android:layout_height="match_parent"
                    android:orientation="horizontal">

                    <ImageView
                        android:id="@+id/imageView18"
                        android:layout_width="0dp"
                        android:layout_height="50dp"
                        android:layout_gravity="center"
                        android:layout_marginLeft="20dp"
                        android:layout_weight="1"
                        app:srcCompat="@drawable/calender" />

                    <TextView
                        android:id="@+id/textView10"
                        android:layout_width="140dp"
                        android:layout_height="match_parent"
                        android:layout_marginLeft="10dp"
                        android:layout_weight="1"
                        android:gravity="center_vertical"
                        android:text="@string/tvAttendance" />

                    <ImageView
                        android:id="@+id/imageView17"
                        android:layout_width="wrap_content"
                        android:layout_height="match_parent"
                        android:layout_weight="1"
                        android:padding="10dp"
                        app:srcCompat="@drawable/right" />
                </LinearLayout>
            </androidx.cardview.widget.CardView>

            <TextView
                android:id="@+id/textView9"
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:layout_marginLeft="20dp"
                android:layout_marginBottom="5dp"
                android:text="@string/titUpcycling" />

            <LinearLayout
                android:layout_width="match_parent"
                android:layout_height="match_parent"
                android:layout_margin="20dp"
                android:orientation="horizontal">

                <androidx.cardview.widget.CardView
                    android:layout_width="108dp"
                    android:layout_height="140dp"
                    android:layout_marginRight="20dp"
                    app:cardBackgroundColor="@color/main"
                    app:cardCornerRadius="8dp"
                    app:cardElevation="0dp"
                    app:cardMaxElevation="0dp" />

                <androidx.cardview.widget.CardView
                    android:layout_width="108dp"
                    android:layout_height="140dp"
                    android:layout_marginRight="20dp"
                    app:cardBackgroundColor="@color/main"
                    app:cardCornerRadius="8dp"
                    app:cardElevation="0dp"
                    app:cardMaxElevation="0dp" />

                <androidx.cardview.widget.CardView
                    android:layout_width="108dp"
                    android:layout_height="140dp"
                    android:layout_marginRight="20dp"
                    app:cardBackgroundColor="@color/main"
                    app:cardCornerRadius="8dp"
                    app:cardElevation="0dp"
                    app:cardMaxElevation="0dp" />
            </LinearLayout>

        </LinearLayout>
    </ScrollView>
</androidx.constraintlayout.widget.ConstraintLayout>
