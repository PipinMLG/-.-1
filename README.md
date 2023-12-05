# -.-1
Синтаксис Swift. Set ( Множества )

import UIKit
import Foundation

var anotherInt = 1...9
anotherInt.count



let range = -100...100
var item : UInt = 21

var range2 = "a"..."z"
range2.lowerBound
range2.upperBound


let lineArray = Array(1...10)
let repeatArray = Array(repeating: "Swift", count: 5)
repeatArray
var multiArray = [1, 5, 9, 8, 0, 67, 28877]
multiArray[5] = 122
multiArray

let a1 = 1
let a2 = 2
let a3 = 3
var someArray = [1, 2, 3]

someArray == [a1,a2,a3]
var numArray = [1,2,3,4,5]
var sliceOfArray = numArray[numArray.count-3...numArray.count-1]
var subArray = numArray.suffix(3)
numArray.first
numArray.last
numArray.append(6)
numArray.insert(100, at: 2)
numArray.removeLast()
numArray.removeFirst()
numArray.remove(at: 2)
numArray

var words = [String](arrayLiteral: "a","b","c")
let array = Array(1..<10)


let friends = ["Alex","Anton","Jane"]
print(friends[1])



var arr1 = [Character](arrayLiteral: "a","b","c","d")
arr1.insert("z", at: 1)
var i = UInt8(arr1.count)

var arr = [Array<Character>]()
arr.append(["a", "b", "c"])
arr.append(["d", "e", "f"])
arr.remove(at:1)
var arr2 = arr.remove(at: 0)
print(arr2[0])

var firstArray : [UInt] = [1,2,3,4,5]
var secondArray: [UInt] = firstArray.dropLast()



var dishes : Set<String> = []
dishes.insert("Jazz")

var myMusicSet : Set<String> = ["hip-hop", "jazz", "Rock"]
var removeStyleResult = myMusicSet.remove("hip-hop")
myMusicSet

myMusicSet.contains("jazz")
myMusicSet.contains("rap")
myMusicSet.count

let oddDigits : Set = [1,3,5,7,9]
let evenDigits : Set = [0,2,4,6,8]
let differrentDigits : Set = [3,4,7,8]

let inter = differrentDigits.intersection(oddDigits)
let inter2 = differrentDigits.symmetricDifference(oddDigits)
inter2
let union = evenDigits.union(oddDigits)
let subtract = differrentDigits.subtracting(evenDigits)


let aSet : Set = [1,2,3,4,5]
let bSet : Set = [1,3]
let cSet : Set = [5,6,7,8]


bSet.isSubset(of: aSet)
aSet.isSuperset(of: bSet)
bSet.isDisjoint(with: cSet)


let setOfNumbers1 = [1,2,4,5,67,8,32,54,6]
let sortaedArray = setOfNumbers1.sorted()
type(of: sortaedArray)


var mySet2: Set = [13.4, 15.1]
print( mySet2.contains( Double(13.4) ) )
var taskSet1 : Set = [1,2,3,4,5,6,7,8,9,10]
var taskSet2 : Set = [5,6,7,8,9,10,11,12,13,14,15]
var taskSet3 = taskSet1.union(taskSet2)
var taskSet4 = taskSet1.symmetricDifference(taskSet2)
var result = UInt8(taskSet4.count)
type(of: result)
result
