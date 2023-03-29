(package "dall-e"
         "0.1.0"
         "Use DALL-E inside Emacs")

(website-url "https://github.com/emacs-openai/dall-e")
(keywords "comm" "dall-e")

(package-file "dall-e.el")
(files "dall-e-*.el")

(script "test" "echo \"Error: no test specified\" && exit 1")

(source 'jcs-elpa)
(source 'gnu)
(source 'melpa)

(depends-on "emacs" "27.1")
(depends-on "openai")
(depends-on "lv")
(depends-on "ht")
(depends-on "spinner")
(depends-on "reveal-in-folder")
(depends-on "async")

(setq network-security-level 'low)  ; see https://github.com/jcs090218/setup-emacs-windows/issues/156#issuecomment-932956432
