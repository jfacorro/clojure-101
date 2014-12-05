;; gorilla-repl.fileformat = 1

;; **
;;; <div style="text-align: center">
;;;   <h1>Clojure 101</h1>
;;;   <img src="http://upload.wikimedia.org/wikipedia/commons/thumb/1/1a/Clojure-glyph.svg/512px-Clojure-glyph.svg.png" width="150" align="middle"/>
;;; </div>
;; **

;; **
;;; ## What is it...?
;;; 
;;; - Lisp Dialect.
;;; - Runs on the Java Virtual Machine (and JavaScript, and .NET's CLR, and...).
;;; - Open Source.
;;; 
;;; ## ...good for?
;;; 
;;; - Expresiveness.
;;; - Conciseness.
;;; - Interactiveness.
;;; - Liveness.
;;; - Happiness.
;;; - And many more -nesses.
;; **

;; **
;;; ### Numbers
;; **

;; @@
42
;; @@
;; =>
;;; {"type":"html","content":"<span class='clj-long'>42</span>","value":"42"}
;; <=

;; @@
42.0
;; @@
;; =>
;;; {"type":"html","content":"<span class='clj-double'>42.0</span>","value":"42.0"}
;; <=

;; @@
42N
;; @@
;; =>
;;; {"type":"html","content":"<span class='clj-bigint'>42N</span>","value":"42N"}
;; <=

;; @@
42.0M
;; @@
;; =>
;;; {"type":"html","content":"<span class='clj-bigdecimal'>42.0M</span>","value":"42.0M"}
;; <=

;; @@
1/3
;; @@
;; =>
;;; {"type":"html","content":"<span class='clj-ratio'>1/3</span>","value":"1/3"}
;; <=

;; **
;;; ### Strings
;; **

;; @@
"Hello"
;; @@
;; =>
;;; {"type":"html","content":"<span class='clj-string'>&quot;Hello&quot;</span>","value":"\"Hello\""}
;; <=

;; @@
(type "Hello Inakos")
;; @@
;; =>
;;; {"type":"html","content":"<span class='clj-class'>java.lang.String</span>","value":"java.lang.String"}
;; <=

;; **
;;; ### Keywords & Symbols
;; **

;; @@
:first-name
;; @@
;; =>
;;; {"type":"html","content":"<span class='clj-keyword'>:first-name</span>","value":":first-name"}
;; <=

;; @@
(quote this-is-a-symbol)
;; @@
;; =>
;;; {"type":"html","content":"<span class='clj-symbol'>this-is-a-symbol</span>","value":"this-is-a-symbol"}
;; <=

;; @@
'this-is-a-symbol
;; @@
;; =>
;;; {"type":"html","content":"<span class='clj-symbol'>this-is-a-symbol</span>","value":"this-is-a-symbol"}
;; <=

;; @@
this-will-fail
;; @@

;; **
;;; ### Syntax & Evaluation
;;; 
;;; <img src="http://i.imgur.com/kbyRlex.png?1">
;; **

;; @@
(+ 1 1)
;; @@
;; =>
;;; {"type":"html","content":"<span class='clj-long'>2</span>","value":"2"}
;; <=

;; @@
+
;; @@
;; =>
;;; {"type":"html","content":"<span class='clj-unkown'>#&lt;core$_PLUS_ clojure.core$_PLUS_@598e851e&gt;</span>","value":"#<core$_PLUS_ clojure.core$_PLUS_@598e851e>"}
;; <=

;; @@
1
;; @@
;; =>
;;; {"type":"html","content":"<span class='clj-long'>1</span>","value":"1"}
;; <=

;; @@
1
;; @@
;; =>
;;; {"type":"html","content":"<span class='clj-long'>1</span>","value":"1"}
;; <=

;; @@
(2 1 1)
;; @@

;; @@
'(+ 1 1)
;; @@
;; =>
;;; {"type":"html","content":"<span class='clj-class'>clojure.lang.PersistentList</span>","value":"clojure.lang.PersistentList"}
;; <=

;; @@
(eval '(+ 1 1))
;; @@
;; =>
;;; {"type":"html","content":"<span class='clj-long'>2</span>","value":"2"}
;; <=

;; **
;;; ## Collections
;;; 
;;; ### Lists
;; **

;; @@
(list 1 2)
;; @@
;; =>
;;; {"type":"list-like","open":"<span class='clj-list'>(</span>","close":"<span class='clj-list'>)</span>","separator":" ","items":[{"type":"html","content":"<span class='clj-long'>1</span>","value":"1"},{"type":"html","content":"<span class='clj-long'>2</span>","value":"2"}],"value":"(1 2)"}
;; <=

;; @@
'(1 2)
;; @@
;; =>
;;; {"type":"list-like","open":"<span class='clj-list'>(</span>","close":"<span class='clj-list'>)</span>","separator":" ","items":[{"type":"html","content":"<span class='clj-long'>1</span>","value":"1"},{"type":"html","content":"<span class='clj-long'>2</span>","value":"2"}],"value":"(1 2)"}
;; <=

;; **
;;; ### Vectors
;; **

;; @@
(vector 1 1)
;; @@
;; =>
;;; {"type":"list-like","open":"<span class='clj-vector'>[</span>","close":"<span class='clj-vector'>]</span>","separator":" ","items":[{"type":"html","content":"<span class='clj-long'>1</span>","value":"1"},{"type":"html","content":"<span class='clj-long'>1</span>","value":"1"}],"value":"[1 1]"}
;; <=

;; @@
[1 1]
;; @@
;; =>
;;; {"type":"list-like","open":"<span class='clj-vector'>[</span>","close":"<span class='clj-vector'>]</span>","separator":" ","items":[{"type":"html","content":"<span class='clj-long'>1</span>","value":"1"},{"type":"html","content":"<span class='clj-long'>1</span>","value":"1"}],"value":"[1 1]"}
;; <=

;; **
;;; ### Maps
;; **

;; @@
(array-map :volley :very-good :pingi-pongi :not-so-good)
;; @@
;; =>
;;; {"type":"list-like","open":"<span class='clj-map'>{</span>","close":"<span class='clj-map'>}</span>","separator":", ","items":[{"type":"list-like","open":"","close":"","separator":" ","items":[{"type":"html","content":"<span class='clj-keyword'>:volley</span>","value":":volley"},{"type":"html","content":"<span class='clj-keyword'>:very-good</span>","value":":very-good"}],"value":"[:volley :very-good]"},{"type":"list-like","open":"","close":"","separator":" ","items":[{"type":"html","content":"<span class='clj-keyword'>:pingi-pongi</span>","value":":pingi-pongi"},{"type":"html","content":"<span class='clj-keyword'>:not-so-good</span>","value":":not-so-good"}],"value":"[:pingi-pongi :not-so-good]"}],"value":"{:volley :very-good, :pingi-pongi :not-so-good}"}
;; <=

;; @@
{:volley :very-good, :pingi-pongi :not-so-good}
;; @@
;; =>
;;; {"type":"list-like","open":"<span class='clj-map'>{</span>","close":"<span class='clj-map'>}</span>","separator":", ","items":[{"type":"list-like","open":"","close":"","separator":" ","items":[{"type":"html","content":"<span class='clj-keyword'>:volley</span>","value":":volley"},{"type":"html","content":"<span class='clj-keyword'>:very-good</span>","value":":very-good"}],"value":"[:volley :very-good]"},{"type":"list-like","open":"","close":"","separator":" ","items":[{"type":"html","content":"<span class='clj-keyword'>:pingi-pongi</span>","value":":pingi-pongi"},{"type":"html","content":"<span class='clj-keyword'>:not-so-good</span>","value":":not-so-good"}],"value":"[:pingi-pongi :not-so-good]"}],"value":"{:volley :very-good, :pingi-pongi :not-so-good}"}
;; <=

;; **
;;; ### Sets
;; **

;; @@
(set [1 2 3 3 :a :b :c :b])
;; @@
;; =>
;;; {"type":"list-like","open":"<span class='clj-set'>#{</span>","close":"<span class='clj-set'>}</span>","separator":" ","items":[{"type":"html","content":"<span class='clj-long'>1</span>","value":"1"},{"type":"html","content":"<span class='clj-keyword'>:c</span>","value":":c"},{"type":"html","content":"<span class='clj-long'>3</span>","value":"3"},{"type":"html","content":"<span class='clj-long'>2</span>","value":"2"},{"type":"html","content":"<span class='clj-keyword'>:b</span>","value":":b"},{"type":"html","content":"<span class='clj-keyword'>:a</span>","value":":a"}],"value":"#{1 :c 3 2 :b :a}"}
;; <=

;; @@
#{1 2 3 :a :b :c}
;; @@
;; =>
;;; {"type":"list-like","open":"<span class='clj-set'>#{</span>","close":"<span class='clj-set'>}</span>","separator":" ","items":[{"type":"html","content":"<span class='clj-long'>1</span>","value":"1"},{"type":"html","content":"<span class='clj-keyword'>:c</span>","value":":c"},{"type":"html","content":"<span class='clj-long'>3</span>","value":"3"},{"type":"html","content":"<span class='clj-long'>2</span>","value":"2"},{"type":"html","content":"<span class='clj-keyword'>:b</span>","value":":b"},{"type":"html","content":"<span class='clj-keyword'>:a</span>","value":":a"}],"value":"#{1 :c 3 2 :b :a}"}
;; <=

;; @@
#{1 1}
;; @@

;; **
;;; ### Seqs
;; **

;; @@
(seq (list 1 :2 "3"))
;; @@
;; =>
;;; {"type":"list-like","open":"<span class='clj-list'>(</span>","close":"<span class='clj-list'>)</span>","separator":" ","items":[{"type":"html","content":"<span class='clj-long'>1</span>","value":"1"},{"type":"html","content":"<span class='clj-keyword'>:2</span>","value":":2"},{"type":"html","content":"<span class='clj-string'>&quot;3&quot;</span>","value":"\"3\""}],"value":"(1 :2 \"3\")"}
;; <=

;; @@
(seq [:1 "2" 3])
;; @@
;; =>
;;; {"type":"html","content":"<span class='clj-unkown'>(:1 &quot;2&quot; 3)</span>","value":"(:1 \"2\" 3)"}
;; <=

;; @@
(seq {:name "Inaka" :country "Argentina"})
;; @@
;; =>
;;; {"type":"html","content":"<span class='clj-unkown'>([:name &quot;Inaka&quot;] [:country &quot;Argentina&quot;])</span>","value":"([:name \"Inaka\"] [:country \"Argentina\"])"}
;; <=

;; @@
(seq #{:1 :a "3"})
;; @@
;; =>
;;; {"type":"html","content":"<span class='clj-unkown'>(&quot;3&quot; :1 :a)</span>","value":"(\"3\" :1 :a)"}
;; <=

;; **
;;; ## Functions
;; **

;; @@
(fn [x]
    (str "Wazzaaaaaa " x "!"))
;; @@
;; =>
;;; {"type":"html","content":"<span class='clj-unkown'>#&lt;clojure_101$eval6209$fn__6210 clojure_101$eval6209$fn__6210@200826&gt;</span>","value":"#<clojure_101$eval6209$fn__6210 clojure_101$eval6209$fn__6210@200826>"}
;; <=

;; @@
(def wazzzup
  (fn [x]
    (str "Wazzaaaaaa " x "!")))
;; @@
;; =>
;;; {"type":"html","content":"<span class='clj-var'>#&#x27;clojure-101/wazzzup</span>","value":"#'clojure-101/wazzzup"}
;; <=

;; @@
(defn wazzzup [x]
  (str "Wazzaaaadsdsadsaaa " x "!"))
;; @@
;; =>
;;; {"type":"html","content":"<span class='clj-var'>#&#x27;clojure-101/wazzzup</span>","value":"#'clojure-101/wazzzup"}
;; <=

;; @@
(wazzzup "Inaka")
;; @@
;; =>
;;; {"type":"html","content":"<span class='clj-string'>&quot;Wazzaaaadsdsadsaaa Inaka!&quot;</span>","value":"\"Wazzaaaadsdsadsaaa Inaka!\""}
;; <=

;; **
;;; ### Common Higher Order Functions (HOFs)
;; **

;; @@
(map wazzzup ["@amilcar", "@euen", "@nacho", "..."])
;; @@
;; =>
;;; {"type":"list-like","open":"<span class='clj-lazy-seq'>(</span>","close":"<span class='clj-lazy-seq'>)</span>","separator":" ","items":[{"type":"html","content":"<span class='clj-string'>&quot;Wazzaaaaaa @amilcar!&quot;</span>","value":"\"Wazzaaaaaa @amilcar!\""},{"type":"html","content":"<span class='clj-string'>&quot;Wazzaaaaaa @euen!&quot;</span>","value":"\"Wazzaaaaaa @euen!\""},{"type":"html","content":"<span class='clj-string'>&quot;Wazzaaaaaa @nacho!&quot;</span>","value":"\"Wazzaaaaaa @nacho!\""},{"type":"html","content":"<span class='clj-string'>&quot;Wazzaaaaaa ...!&quot;</span>","value":"\"Wazzaaaaaa ...!\""}],"value":"(\"Wazzaaaaaa @amilcar!\" \"Wazzaaaaaa @euen!\" \"Wazzaaaaaa @nacho!\" \"Wazzaaaaaa ...!\")"}
;; <=

;; @@
(filter pos? [2 1 0 -1 -2])
;; @@
;; =>
;;; {"type":"list-like","open":"<span class='clj-lazy-seq'>(</span>","close":"<span class='clj-lazy-seq'>)</span>","separator":" ","items":[{"type":"html","content":"<span class='clj-long'>2</span>","value":"2"},{"type":"html","content":"<span class='clj-long'>1</span>","value":"1"}],"value":"(2 1)"}
;; <=

;; @@
(apply str [1 2 3]) ;; == (str 1 2 3)
;; @@
;; =>
;;; {"type":"html","content":"<span class='clj-string'>&quot;123&quot;</span>","value":"\"123\""}
;; <=

;; @@
(def plus-2 (comp inc inc))
(plus-2 1)
;; @@
;; =>
;;; {"type":"html","content":"<span class='clj-long'>3</span>","value":"3"}
;; <=

;; **
;;; ### Example
;;; 
;;; Given a string of comma separated integers, write a function which returns a new comma separated string that only contains the numbers which are perfect squares.
;; **

;; @@
(def x "4,5,6,7,8,9")
;; @@
;; =>
;;; {"type":"html","content":"<span class='clj-var'>#&#x27;clojure-101/x</span>","value":"#'clojure-101/x"}
;; <=

;; @@
(defn split [s] (.split s ","))
;; @@
;; =>
;;; {"type":"html","content":"<span class='clj-var'>#&#x27;clojure-101/split</span>","value":"#'clojure-101/split"}
;; <=

;; @@
(seq (split x))
;; @@
;; =>
;;; {"type":"list-like","open":"<span class='clj-list'>(</span>","close":"<span class='clj-list'>)</span>","separator":" ","items":[{"type":"html","content":"<span class='clj-string'>&quot;4&quot;</span>","value":"\"4\""},{"type":"html","content":"<span class='clj-string'>&quot;5&quot;</span>","value":"\"5\""},{"type":"html","content":"<span class='clj-string'>&quot;6&quot;</span>","value":"\"6\""},{"type":"html","content":"<span class='clj-string'>&quot;7&quot;</span>","value":"\"7\""},{"type":"html","content":"<span class='clj-string'>&quot;8&quot;</span>","value":"\"8\""},{"type":"html","content":"<span class='clj-string'>&quot;9&quot;</span>","value":"\"9\""}],"value":"(\"4\" \"5\" \"6\" \"7\" \"8\" \"9\")"}
;; <=

;; @@
(defn parse-int [s] (Integer/parseInt s))
;; @@
;; =>
;;; {"type":"html","content":"<span class='clj-var'>#&#x27;clojure-101/parse-int</span>","value":"#'clojure-101/parse-int"}
;; <=

;; @@
(parse-int "12")
;; @@
;; =>
;;; {"type":"html","content":"<span class='clj-unkown'>12</span>","value":"12"}
;; <=

;; @@
(defn perfect-square? [i]
  (zero? (mod i (Math/sqrt i))))
;; @@
;; =>
;;; {"type":"html","content":"<span class='clj-var'>#&#x27;clojure-101/perfect-square?</span>","value":"#'clojure-101/perfect-square?"}
;; <=

;; @@
(perfect-square? 17)
;; @@
;; =>
;;; {"type":"html","content":"<span class='clj-unkown'>false</span>","value":"false"}
;; <=

;; @@
(perfect-square? 25)
;; @@
;; =>
;;; {"type":"html","content":"<span class='clj-unkown'>true</span>","value":"true"}
;; <=

;; @@
(interpose "," [1 2])
;; @@
;; =>
;;; {"type":"list-like","open":"<span class='clj-lazy-seq'>(</span>","close":"<span class='clj-lazy-seq'>)</span>","separator":" ","items":[{"type":"html","content":"<span class='clj-long'>1</span>","value":"1"},{"type":"html","content":"<span class='clj-string'>&quot;,&quot;</span>","value":"\",\""},{"type":"html","content":"<span class='clj-long'>2</span>","value":"2"}],"value":"(1 \",\" 2)"}
;; <=

;; @@
(apply str [1 "," 2])
;; @@
;; =>
;;; {"type":"html","content":"<span class='clj-string'>&quot;1,2&quot;</span>","value":"\"1,2\""}
;; <=

;; @@
(apply str
       (interpose "," 
                  (filter perfect-square?
                          (map parse-int
                               (split x)))))
;; @@
;; =>
;;; {"type":"html","content":"<span class='clj-string'>&quot;4,9&quot;</span>","value":"\"4,9\""}
;; <=

;; @@
(->> x
     split
     (map parse-int)
     (filter perfect-square?)
     (interpose ",")
     (apply str))
;; @@
;; =>
;;; {"type":"html","content":"<span class='clj-string'>&quot;4,9&quot;</span>","value":"\"4,9\""}
;; <=

;; @@

;; @@
