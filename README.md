# Machinist X99 RS9 (rev 5.1) modbios

Стоковый BIOS и его модификация для материнской платы Machinist X99 RS9 ревизии 5.1. Номер ревизии на данной плате слева внизу разъема питания 24 pin.

![image](https://github.com/user-attachments/assets/d3b18257-a611-4d2a-9a55-692555741db9)

![image](https://github.com/user-attachments/assets/cd1c5afe-f017-440b-abde-5b2f5696e368)


# Список файлов:
- stock.bin - стоковый файл BIOS сняты с данной платы. На плате автора установлен чипсет Q87;
- mod.bin - модифицированый файл BIOS, основанный на стоковой версии BIOS данной платы.

# Что изменено в модификации:
- андервольт -50 мВ;
- разблокировка турбобуста на все ядра;
- параметр Package C state limit по умолчанию выставлен в С2;
- CPU C3 report по умолчанию включен;
- CPU C6 report по умолчанию выключен.
