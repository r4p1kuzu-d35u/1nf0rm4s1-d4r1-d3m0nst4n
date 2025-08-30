# media viewer

## 📄 Kode untuk menambahkan text amja

```html
<div class="bg-gradient-to-br from-gray-900 to-black border border-red-800 rounded-xl p-6 mb-8 shadow-2xl media-hover hover:border-red-600 hover:shadow-red-900/50">
                    <h3 class="text-2xl font-semibold mb-3 text-red-300">Text1</h3>
                    <p class="text-gray-300 mb-4 leading-relaxed">description</p>
                </div>
```


## 📄 Kode untuk menambahkan gambar

```html
<div class="bg-gradient-to-br from-gray-900 to-black border border-red-800 rounded-xl p-6 mb-8 shadow-2xl media-hover hover:border-red-600 hover:shadow-red-900/50">
                    <h3 class="text-2xl font-semibold mb-3 text-red-300">Image</h3>
                    <p class="text-gray-300 mb-4 leading-relaxed">description</p>
                    <div class="overflow-hidden rounded-lg shadow-lg">
                        <img src="your image source" 
                             alt="Image" 
                             class="w-full h-auto max-w-full rounded-lg transition-transform duration-300 hover:scale-105"
                             loading="lazy">
                    </div>
                </div>
```

## 📄 Kode untuk menambahkan video

```html
  <div class="bg-gradient-to-br from-gray-900 to-black border border-red-800 rounded-xl p-6 mb-8 shadow-2xl media-hover hover:border-red-600 hover:shadow-red-900/50">
                    <h3 class="text-2xl font-semibold mb-3 text-red-300">Video</h3>
                    <p class="text-gray-300 mb-4 leading-relaxed">description</p>
                    <div class="rounded-lg overflow-hidden shadow-lg">
                        <video class="w-full max-w-full h-auto rounded-lg bg-black" 
                               controls 
                               preload="metadata">
                            <source src="Your video source" type="video/mp4">
                            Browser Anda tidak mendukung tag video.
                        </video>
                    </div>
                </div>
```

## 📄 Kode untuk menambahkan audio

```html
<div class="bg-gradient-to-br from-gray-900 to-black border border-red-800 rounded-xl p-6 mb-8 shadow-2xl media-hover hover:border-red-600 hover:shadow-red-900/50">
                    <h3 class="text-2xl font-semibold mb-3 text-red-300">Audio1</h3>
                    <p class="text-gray-300 mb-4 leading-relaxed">description</p>
                    <div class="bg-gradient-to-r from-red-950 to-black p-4 rounded-lg shadow-inner">
                        <audio class="w-full" 
                               controls 
                               preload="metadata"
                               style="filter: sepia(1) hue-rotate(320deg) brightness(1.2);">
                            <source src="Your audio source" type="audio/mpeg">
                            Browser Anda tidak mendukung elemen audio.
                        </audio>
                    </div>
                </div>
```
