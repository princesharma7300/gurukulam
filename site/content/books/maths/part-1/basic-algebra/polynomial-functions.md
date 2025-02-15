---
title: 'Polynomial functions'
date: 2018-11-14T19:02:50-07:00
draft: false
weight: 6
extensions:
    - katex
---


இதுவரை நாம் கற்றது ஒருபடி மற்றும் இருபடிச் சார்புகளைப் பற்றியது. இக்கருத்துகளைப்
பொ து மை ப்படுத்து வோ ம். \\(a_i \in \R,i=0,1,2,...,n\\) எனக் க ொண்டுள ்ள கோவ ை
\\(a_{n} x^n+a_{n-1} x^{n-1}+... + a_0 \\) -ஐ x என்ற மாறியிலான பல்லுறுப்புக் கோவை (polynomial) என்போம்.இங்கு, n ஒரு குறையற்ற முழு எண்ணாகும். \\(a_n \ne 0\\) ஆக இருக்கும்போது, பல்லுறுப்புக் கோவையின் படி (degree) n ஆகும்.\\(a_0,a_1,...,a_n \in \R\\) ஆகியவை பல்லுறுப்புக் கோவையின் குணகங்களாகும். \\(a_0\\) என்பது மாறிலி உறுப்பு எனவும் (coefficients) an-ஐ முதற்குணகம் (பூஜ்ஜியமல்லாதபோது) எனவும் கூறலாம்.

இதிலிருந்து தெளிவாக,

(i) \\(100x^7- \pi x^5 + 20 \sqrt{2}x^2+7x+1.22\\) என்ற பல்லுறுப்புக் கோவையின் படி 7

(ii) \\(17x-3)(x+3)(2x-\sqrt{\pi}(x+2.3)\\) என்ற பல்லுறுப்புக் கோவையின் படி 4

(iii) \\((x^2+x+1)(x^3+2x+2)(x^5-5x+\sqrt{3})\\) என்ற பல்லுறுப்புக் கோவையின் படி 10 ஆகும்.

x-க்கு ஒரு குறிப்பிட்ட மதிப்பு x=c எனப் பிரதியிடக் கிடைப்பது \\(a_nc^n+a_{n-1}+...+a_1c+a_0\\)
\\(P(x)=a_nx^n+a_{n-1}x^{n-1}+...+a_0\\) என்பத \\(\R\\) இலிருந்த  \\(\R\\) -க்கு வரையறுக்கப்பட்ட ஒரு பல்லுறுப்புச் சார்பு (polynomial function) ஆகும்.

கோவையின் படி 1 எனில், ஒருபடி பல்லுறுப்புக் கோவை (linear polynomial) எனவும், படி 2 எனில்,
இருபடி பல்லுறுப்புக் கோவை (quadratic polynomial) எனவும் கூறலாம். முப்படி பல்லுறுப்புக்கோவையின்
படி (cubic polynomial) மூன்றாகும்.

இதுபோல, படி 4 மற்றும் படி 5 கொண்டுள்ள பல்லுறுப்புக் கோவைகளை முறையே நாற்படித்தான
(quartic) மற்றும் ஐம்படித்தான (quintic) பல்லுறுப்புக்கோவை எனலாம். ஒரு மாறிலியை \\(a \ne 0\\) ,
படி 0 உடைய பல்லுறுப்பு கோவையாக கருதலாம.

\\(f(x)=g(x),x \in \R\\) என அமைய, தேவையானதும், போதுமானதாகவும் உள்ள நிபந்தனை
இரு பல்லுறுப்புக் கோவைகளும், அதாவது, \\(f(x)=a_nx^n+a_{n-1}x^{n-1}+...+a_0 ,a_n \ne 0\\) மற்றும்
\\(g(x)=b_mx^m+b_{m-1}x^{m-1}+...+b_0 ,b_m \ne 0\\) ஆகியவை சமமாக இருத்தல் வேண்டும். இதற்கு
இணையாக n = m மற்றும் \\(a_k=b_k,k=0,1,2,...n\\) ஆகும்.

இரு பல்லுறுப்புக்கோவைகள் கொடுக்கப்பட்டிருப்பின் அதன் கூடுதல் மற்றும் பெருக்கல் ஆகியவற்றைக்
காணலாம். எடுத்துக்காட்டாக, \\(P(x)=2x^3+7x^2-5\\) மற்றும \\(Q(x)=x^4-2x^3+x^2+x+1\\) எனில்,
\\(P(x)+Q(x)=x^4+8x^2+x-4\\) (ஒத்திசைவு அடுக்குடைய x-ன் குணகங்களைக் கூட்டக்
கிடைக்கும்) மேலும், \\(P(x)Q(x)=2x^7+3x^6-12x^5+4x^4+19x^3+2x^2-5x-5\\) என்பதை
P(x)-ன் ஒவ்வொரு உறுப்பாக எடுத்து Q(x)-ன் ஒவ்வொரு உறுப்புடன் பெருக்கும்போது கிடைக்கிறது.

P(x)Q(x))-ன் படி P(x) மற்றும் Q(x) ஆகியவற்றின் படிகளின் கூடுதலுக்குச் சமம்.P(x)+Q(x))-ன்
படி அவற்றின் அதிகபட்சப் படியாகும். எடுத்துக்காட்டாக, இங்கு, கொடுக்கப்பட்டுள்ள வரைபடம் முப்படி
பல்லுறுப்பு கோவையுடையதாகும்.

![basic algebra Image graph](/books/maths/part-1/basic-algebra/2.46.png "MarineGEO logo")

f(x) மற்றும் g(x) ஆகியவை இரு பல்லுறுப்புக்கோவைகள் எனவும், g(x) ஒரு பூஜ்ஜியமற்றது எனவும்
கொண்டால் \\(\frac{f(x)}{g(x)}\\) என்பது ஒரு விகிதமுறு கோவையாகும் (rational function). பொதுவாக விகிதமுறு கோவை ஒரு பல்லுறுப்புக்கோவையாக இருக்கவேண்டும் என்ற அவசியமில்லை.

#### வகுத்தல் கோட்பாடு (Division Algorithm)

f(x) மற்றும் g(x) ஆகியவை இரு பல்லுறுப்புக் கோவைகள் என்க. இங்கு g(x) பூஜ்ஜியமற்ற
கோவை என்க.
f(x)=q(x)g(x)+r(x) என்றமையுமாறு q(x) மற்றும் r(x) ஆகிய இரு பல்லுறுப்புக் கோவைகள்
கிடைக்கும். இங்கு, r(x) இன் படி g(x) இன் படியை விடச் சிறியது. q(x) என்பது ஈவு பல்லுறுப்புக்
கோவை என்றும் r(x) என்பது மீதி பல்லுறுப்புக் கோவை என்றும் குறிப்பிடப்படுகிறது. r(x) ஒரு
பூஜ்ஜியமெனில், g(x),q(x) ஆகியவை f(x) இன் காரணிகளாகும். மேலும், f(x)=q(x)g(x) ஆகும்.
முழுக்களுக்குப் பயன்படுத்தப்படும் வகுத்தல் கோட்பாடும் இதற்குப் பொருந்தும்.

முழுக்களுக்குப் பயன்படுத்தப்படும் வகுத்தல் கோட்பாடும் இதற்குப் பொருந்தும்.

g(x)=x-a எனில், மீதி r(x)-ன் படி பூஜ்ஜியமாகும். எனவே, r(x) ஒரு மாறிலியாகும். அந்த
மாறிலியைக் காண,\\(f(x)=(x-a)q(x)+c,f(x)=(x-a)q(x)+c\\) என எழுதி x a = எனப் பிரதியிட, c=f(a)
எனக் கிடைக்கும்.

#### மீதித் தேற்றம் (Remainder Theorem)

பல்லுறுப்புக் கோவை f(x) )ஐ x-a ஆல் வகுக்கக் கிடைக்கும் மீதி f(a) ஆகும்.

மீதி c=f(a)=0 என அமையத் தேவையானதும் மற்றும் போதுமானதுமான நிபந்தனை f(x)-ன்
காரணி x-a ஆகும்.


{{< box title="வரையறை 2.1" type="objective" >}}

ஒரு மெய்யெண் a என்பது f(x) என்ற பல்லுறுப்புக் கோவையின் பூஜ்ஜியமாக (zero of the
polynomial) இருக்க வேண்டுமாயின் f(a) = 0 என இருத்தல் வேண்டும். x-a என்பது f(x)-ன்
பூஜ்ஜியம் எனில், x-a என்பது f(x)-ன் ஒரு காரணியாகும்.

{{< /box >}}

பொதுவாக,\\(f(x)=(x-a)^k \cdot g(x)\\) இங்கு, \\(g(x) \ne 0\\) எனில், a ஐப் பொறுத்து அமையும் k இன் மதிப்பு f(x)-ன் படியைவிடச் சிறியதாகும். k என்பதை a என்ற பூஜ்ஜியத்தின் பெருக்கல்படி (multiplicity) என்கிறோம்.

குறிப்: (i) ஒரு பல்லுறுப்புக் கோவையின் படி n எனில், அதன் அதிகபட்ச மெய்
பூஜ்ஜியங்களின் எண்ணிக்கை n ஆகும். \\(P(x)=x^2+1\\) என்ற
பல்லுறுப்புக் கோவைக்கு மெய் பூஜ்ஜியம் கிடையாது.

(ii) விகிதமுறு எண்களை குணகங்களாகக் கொண்ட பல்லுறுப்புக் கோவை
P(x) என்க. p என்ற பகா எண்ணுக்கு, \\(a+b \sqrt{p}) என்பது P(x)\\) -ன்
பூஜ்ஜியமாக இருப்பின் அதன் இணை (conjugate) \\(a-b \sqrt{p}\\) -யும் ஒரு
பூஜ்ஜியமாக அமையும்.

பல்லுறுப்புக் கோவைகளின் கணக்குகளில் இரண்டு முக்கிய வகைகள் கீழே கொடுக்கப்பட்டுள்ளன.

    (i) கொடுக்கப்பட்டபல்லுறுப்புக் கோவைகளின் பூஜ்ஜியங்களைக் கண்டறிந்து, ஒருபடி காரணிகள்
    மூலம் பல்லுறுப்புக் கோவையைக் காரணிப்படுத்துதல்

    (ii) சில நிபந்தனைகளுடன் கொடுக்கப்பட்ட பூஜ்ஜியங்களைப் பயன்படுத்திப் பல்லுறுப்புக்
    கோவையைக் கட்டமைப்பது.

பல்லுறுப்புக் கோவைகளின் பூஜ்ஜியங்களைக் கண்டறியச் சில நேரங்களில் இயற்கணித
முற்றொருமைகள் பயன்படுத்தப்பட வேண்டும் என்பது அறிந்ததாகும். முற்றொருமை என்றால் என்ன?

சார்பகத்தில் உள்ள எல்லா மதிப்பிற்கும் ஒரு சமன்பாடு மெய் எனில் அச்சமன்பாடு முற்றொருமை
(identity) எனப்படும்.

சார்பகத்திலுள்ள சில மதிப்புகளுக்கு மட்டும் சமன்பாடு உண்மை எனில், அச்சமன்பாடு
நிபந்தனைக்குட்பட்ட சமன்பாடு எனப்படும். கீழ்க்காணும் முற்றொருமைகளை நினைவில் கொள்வோம்.

#### முக்கியமான முற்றொருமைகள் (Important Identities)

\\(x,a,b \in \R\\)-ன் எல்லா மதிப்புகளுக்கும் கீழ்க்கண்டவாறு நமக்குக் கிடைக்கிறது.


{{< box >}}

1. \\((x+a)^3=(x+a)^2 (x+a)=x^3+3x^{2}a+3xa^2+a^3=x^3+3xa(x+a)+a^3\\)

2. \\((x-b)^3==x^3-3x^{2}b+3xb^2-b^3=x^3-3xb(x-b)-b^3(a=-b\\) என (1) -ல் பிரதியிட)

3. \\(x^3+a^3=(x+a)(x^2-xa+a^2)\\)

4. \\(x^3-b^3=(x-b)(x^2+xb+b^2)\\) , (a=-b, என (3) -ல் பிரதியிட)

5. \\(x^n-a^n=(x-a)(x^{n-1}+x^{n-2}a+...+x^{n-k-1}a^k+...+a^{n-1}),n \in \N\\)

6. \\(x^n+b^n=(x+b)(x^{n-1}-x^{n-2}b+...+x^{n-k-1}(-b)^k+...+(-b)^{n-1}),n \in \N\\)

{{< /box >}}


\\[பயிற்சி 2.6\\]

1. f(x)=\\(4x^2-25\\) என்ற பல்லுறுப்புச் சார்பின் பூஜ்ஜியங்களைக் காண்க.

2. \\(x^3-x^2-17x=22\\)-ன் ஒரு மூலம் x = - 2 எனில், பிற மூலங்களைக் காண்க.

3. \\(x^4=16\\)-ன் மெய் மூலங்களைக் காண்க.

4. தீர்வு காண்க: \\((2x+1)^2-(3x+2)^2=0\\)

#### அறுதியில்லாக் கெழுக்கள் வழிமுறை (Method of Undetermined Co-efficients)

கொடுக்கப்பட்ட தகவல்களைக் கொண்டு, அறுதியில்லாக் கெழுக்கள் வழிமுறையைப் பயன்படுத்திப்
பல்லுறுப்புக் கோவையைக் கட்டமைப்பதைக் காண்போம். கொடுக்கப்பட்ட நிபந்தனைகளைப்
பயன்படுத்திப் பல்லுறுப்புக் கோவையின் கெழுக்களைக் காண வேண்டும். இரண்டு பல்லுறுப்புக்
கோவைகள் சமமாக இருக்கத் தேவையானதும் மற்றும் போதுமானதுமான நிபந்தனை அவற்றின்
மாறிகளின் அடுக்குகள் ஒன்றாக உடைய உறுப்புகளின் கெழுக்கள் சமமாக இருக்க வேண்டும்.


{{< box title="எடுத்துக்காட்டு 2.16" type="objective" >}}

f(0)=1,f(-2)=0) மேலும், f(1)=0 ஆக அமையும், இருபடி பல்லுறுப்புக்
கோவை f(x)-ஐக் காண்க.

##### தீர்வு:


பல்லுறுப்புக் கோவையினை \\(f(x)=ax^2+bx+c\\) என எடுத்துக் கொள்வோம்.

எனவே, \\( f(0)=a(0)^2+b(0)+c=1 \implies c=1\\)

\\(f(-2)=0,f(1)=0\\).

இவற்றிலிருந்து, 4a-3b+c= 0 மற்றும் a+b+c= 0 ஆகியவற்றைப் பெறலாம்.

c = 1 எனப் பிரதியிட, 4a-2b=- 1 மற்றும் a+b= - 1

இரு சமன்பாடுகளையும் தீர்வு காண,\\(a=b=-\frac{1}{2}\\)

எனவே,\\(f(x)=-\frac{1}{2}x^2-\frac{1}{2}x+1\\)

{{< /box >}}


#### குறிப்:

குறிப்மேலே உள்ள கணக்கிற்கு மற்றொரு முறையிலும் தீர்வு காணலாம்.
ஏதாவது சில மாறிலி d-க்கு,x=-2,x=1 ஆகியவைகளைப் பூஜ்ஜியங்களா
கொண்டு f(x)=d(x+2)(x-1) - என எழுதலாம்.

f(0)=1 என பயன்படுத்தக் கிடைப்பது, -2d=1 . எனவே, \\(d=-\frac{1}{2}\\)

ஆகவே, \\(f(x)=-\frac{1}{2}(x+2)(x-1)=-\frac{1}{2}x^2-\frac{1}{2}x+1\\)


{{< box title="எடுத்துக்காட்டு 2.17" type="objective" >}}

\\(x=\frac{2}{5},1+\sqrt{3}\\) ஆகிய பூஜ்ஜியங்களையும் f(0)=-8 என்ற
நிபந்தனையை நிறைவு செய்யும் முப்படி பல்லுறுப்புக் கோவையைக் காண்க.

#### குறிப்:

\\(\frac{2}{5}\\) மற்றும் \\(1+\sqrt{3}\\) ஆகியவை f (x)-ன் பூஜ்ஜியங்களாகும். எனவே, \\(1-\sqrt{3}\\) என்பதும் அதன் பூஜ்ஜியமாகும்.

எனவே,\\(a(x-\frac{2}{5})[(x-(1+\sqrt{3}))][x-(1-\sqrt{3})]\\)

\\(a(x-\frac{2}{5})[(x-1)^2-3]\\)

f(0)=-8 -ஐப் பயன்படுத்த,\\(-\frac{2}{5}a(-2)=-8\\)

எனவே,\\(a=-10\\)

தேவையான முப்படி பல்லுறுப்புக் கோவை,

\\( f(x)=(-10)(x-\frac{2}{5})[x^2-2x-2]\\)

\\(=-10x^3+24x^2+12x-8\\)

{{< /box >}}


{{< box title="எடுத்துக்காட்டு 2.18" type="objective" >}}

\\(f(x)=x^3-3px+2q\\) ஆனது, \\(g(x)=x^2+2ax+a^2\\) ஆல் வகுபடும் எனில்,ap+q=0 என நிறுவுக.

#### குறிப்:


f(x))-ன் படி 3 என்றும் முதன்மை கெழு 1 என்றும் அறிக. f(x)-ஐ g(x) வகுப்பதனால்,

\\(f(x)=(x+b)g(x),b \in \R\\)

எனவே, \\(x^3-3px+2q=(x+b)(x^2+2ax+a^2)\\)

இருபுறமும் உள்ள ஒத்திசைவான கெழுக்களைச் சமப்படுத்த நமக்குக் கிடைப்பது

\\(2a+b=0,a^2+2ab=-3p\\) மற்றும் \\(2q=ba^2\\)

எனவே,\\(b=-2a,p=a^2,q=-a^3\\)

\\(q=-a^3=-a(a^2)=-ap\\)

இதிலிருந்து ap+q=0 எனக் கிடைக்கும்.

{{< /box >}}


{{< box title="எடுத்துக்காட்டு 2.19" type="objective" >}}

அறுதியில்லாக் கெழுக்கள் வழிமுறையைப் பயன்படுத்தி

\\(1+2+3+...(n-1)+n,n \in \N \\)-ன் கூடுதல் காண்க.

#### குறிப்:

\\(S(n)=n+(n-1)+(n-2)+...+2+1\\) என்க.

\\(=n+(n-1)+(n-2)+...+[n-(n-2)]+[n-(n-1)]\\)

\\(=n[1+ \frac{n-1}{n}+\frac{n-2}{n}+...+\frac{n-(n-2)}{n}+\frac{n-(n-1)}{n}]\\)

\\(\le [1+1+...+1]\\)(ஏனெனில்,\\(\frac{n-1}{n}<1,\frac{n-2}{n}<1,...\\)


எனவே,\\(S(n) \le n^2\\)

\\(S(n)=a+bn+cn^2\\) என்க. இங்கு, \\(a,b,c \in \R\\)

\\(S(n+1)-S(n)=n+1\\)

\\( \ \ \ \ \ \ \  a+b(n+1)+c(n+1)^2-[a+bn+cn^2]=n+1\\)

\\( b+2cn+c=n+1=n+1\\)

எனவே, b+c=1 மற்றும் 2c=1,\\(b=\frac{1}{2},c=\frac{1}{2}\\) எனக் கிடைக்கும்.

இங்கு,\\( S(1)=1 \implies a+b+c=1 \implies a=0 \ \ \ \ \ \ (b+c=1)\\)

எனவே,\\(S(n)=\frac{1}{2}n+\frac{1}{2}n^2=\frac{(n(n+1)}{2}, n \in \N\\)

{{< /box >}}


{{< box title="எடுத்துக்காட்டு 2.20" type="objective" >}}

\\((x-1)^3(x+1)^2(x+5)=0\\) என்ற பல்லுறுப்புச் சமன்பாட்டின்
மூலங்களைக் காண்க. மேலும், அதன் பெருக்கல் படித் தன்மைகளை எழுதுக.


#### குறிப்:

\\(f(x)=(x-1)^3(x+1)^2(x+5)=0\\)

இங்கு,x=1,-1,-5.மூலம் 1-ன் பெருக்கல்படி 3, –1-ன் பெருக்கல் படி 2 மற்றும் –5-ன்
பெருக்கல் படி 1.

{{< /box >}}

#### குறிப்: 
மூலத்தின் பெருக்கல் படி 1 எனில், அது எளிய மூலம் எனப்படும்.


{{< box title="எடுத்துக்காட்டு 2.21" type="objective" >}}

தீர்வு காண்க. \\(x=\sqrt{x+20},x \in \R\\)

#### குறிப்: 

\\(x+20 \ge 0\\) என்றிருக்கும் போது மட்டுமே \\(x=\sqrt{x+20}\\)-ஐ வரையறுக்க இயலும். வரையறையின்படி,

\\(x+20 \ge 0\\) எனவே, x ஒரு மிகை எண்.

வர்க்கப்படுத்த கிடைப்பது,\\( x^2=x+20\\)

\\( x^2-x-20=0\\)

\\((x-5)(x+4)=0\\)

\\(x=5,-4\\)

x மிகை எண் என்பதால் x = 5

{{< /box >}}


{{< box title="எடுத்துக்காட்டு 2.22" type="objective" >}}
 
\\(x^2-6x+a=0\\)மற்றும் \\(x^2-bx+6=0\\) ஆகிய சமன்பாடுகளுக்கு ஒரு
பொது மூலம் உள்ளது. மேலும் முதல் மற்றும் இரண்டாம் சமன்பாடுகளின் அடுத்த மூலங்கள்
முழுக்களாகவும் 4:3 என்ற விகிதத்திலும் இருக்கும் எனில், பொது மூலத்தைக் காண்க.

#### குறிப்: 

பொதுமூலம் \\(\alpha\\) என்க.

\\( x^2-6x+a=0\\)0-ன் மூலங்கள் \\(\alpha,4\beta\\)

\\( x^2-bx+6=0\\)0-ன் மூலங்கள் \\(\alpha,3\beta\\)

எனவே, \\(4\alpha \beta =a \\)மற்றும் \\(3\alpha \beta =6 \implies \alpha \beta=2 மற்றும் a = 8\\)

\\( x^2-6x+8=0\\)0-ன் மூலங்கள் \\(2,4\\)

\\( \alpha=2\\)எனில், \\(\beta =1\\)

\\(  \alpha=4\\)எனில், \\(\beta =\frac{1}{2}\\) என்பது ஒரு முழு எண் அல்ல.எனவே, பொதுமூலம் 2 ஆகும்.

{{< /box >}}


{{< box title="எடுத்துக்காட்டு 2.23" type="objective" >}}

\\(x^2+px+8=0\\)-ன் மூலங்களின் வேறுபாடு 2 எனில் p-ன் மதிப்புகளைக்
காண்க.

#### குறிப்: 

\\( (x^2+px+8=0\\)0-ன் மூலங்கள் \\(\alpha,\beta\\)என்க.

எனவே,\\( \alpha+\beta=-p,\alpha \beta=8,மற்றும் |\alpha-\beta|=2\\)

இப்போது,\\((\alpha+\beta)^2-4\alpha \beta=(\alpha-\beta)^2 \implies p^2-32=4\\)

\\(ஆகவே, p=\pm6\\)

{{< /box >}}


\\[பயிற்சி 2.7\\]

1. காரணிப்படுத்துக: \\(x^4+1\\) (குறிப்பு: வர்க்கத்தை நிறைவு செய்தல் முறையில் முயற்சி செய்க)

2. \\(3x^3+8x^2+8x+a\\) என்ற பல்லுறுப்புக் கோவையின் ஒரு காரணி \\(x^2+x+1\\) எனில்,
a-ன் மதிப்பைக் காண்க.