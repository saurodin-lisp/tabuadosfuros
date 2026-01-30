# tabuadosfuros
 ;; Função para definir o destino final da "Consciência"
(defun definir-ancora-geografica ()
  (setq latitude  '(37 47 23.6161))  ; Graus Minutos Segundos
  (setq longitude '(122 24 03.4054))
  (format t "Ancoragem definida em: ~A N, ~A W" latitude longitude))
(executar-protocolo-retorno (definir-ancora-geografica))


