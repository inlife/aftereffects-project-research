# Fold

Fold tag represents a listing of items, which are added to the project. If you make an analogy with GUI, it contains the following structure:

![](https://cdn.discordapp.com/attachments/144520318898143232/403631610915979264/unknown.png)

It consists of `<Item>` tags, sepearted by other unknown fields, possibly showing beginning/end, or position in the list, or no idea what.

```xml
    <Fold>
        <fdta bdata="0000000000000000000000000000"/>
        <Item>
            <idta bdata="000700000000000000000000000000000000000c000000300000000000000000000000000000000000000000000000000000000000000000000005000000000000000000000000000000000000000000d655bb34"/>
            <string/>
            <Pin>
                <sspc bdata="000000000000000000000000000000000000000000005a5045470000000000000500000002d00000000000000258000000000000025800000000000000000018010100000000000000030000000000010000000000000000000000000000000000000000000000000000000000000000002000000000d655bb340000000c0000000100000000000000000001000000010000000000000000000000000000000800000000000000000000000000000000000000000000000000000000ffffffffffffffff0000000100020000000000000009f20b01000000000000000000"/>
                <string/>
                <Als2>
                    <fileReference ascendcount_base="1" ascendcount_target="3" fullpath="D:\Projects\ae-test\nexrender-boilerplate-master\assets\2016-aug-deep.jpg" platform="Win" server_name="inlife-pc" server_volume_name="HDD" target_is_folder="0"/>
                </Als2>
                <opti bdata="5a50454700050000003a00000000000000000000000000000000000000004745504affffffff5241572001000000010000000000000000000000"/>
                <pgui bdata="974ff14f0434432e970b4e3f09223407"/>
                <CLRS>
                    <epid bdata="ffffffffffffffffffffffffffffffff"/>
                    <apid bdata="601e997329e4901f2acc5b497ba315f3"/>
                    <linl bdata="00000000"/>
                    <embp bdata="01"/>
                    <ipws bdata="00"/>
                </CLRS>
                <mnfo>
                    <strt bdata="000000001e000000"/>
                    <drop bdata="01"/>
                </mnfo>
                <string/>
            </Pin>
            <ftgi bdata="0000000000000001ffffffff00000258"/>
            <string/>
            <Gide>
                <gdta bdata="0000000000000000"/>
                <list>
                    <lhd3 bdata="00d00bee000000000000000000000001000000100000000200000001000000020000000000000000000000000000000000000000"/>
                </list>
            </Gide>
        </Item>
        <fvdv bdata="00000003"/>
        <fiop bdata="00"/>
        <ftts bdata="00000000"/>
        <foac bdata="00"/>
        <fiac bdata="00"/>
        <fipc bdata="0000"/>
        <fifl bdata="00000000"/>
        <Item>
        ...
    </Fold>
```

Not empty Fold will always contain at least one Compossition item (depends on how many compositions you've added to the project), more details: [Composition](composition.md).  
Composition takes the most space for xml definition.

Other Items are described there: [Item](item.md)
