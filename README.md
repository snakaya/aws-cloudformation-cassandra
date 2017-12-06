# AWS CloudFormation Template for Cassandra

## What is this?
The Template file of [AWS CloudFormation](https://aws.amazon.com/documentation/cloudformation/) for Cassandra.

## Usage
- Go to [CloudFormation] and press [Create Stack] Button.
- On [Choose a template], Select [Upload a template to Amazon S3] and choose THIS template file.
- You can see the next parameter screen, and Do It.

![Screenshot](https://github.com/snakaya/aws-cloudformation-cassandra/raw/master/cf_cassandra.png)

## Description
- It create Primary Seed Node * 1 + Secondary Seed Node * 1 + Non Seed Node * 1.
- If You want create more Nodes(Seed Node and Non Node), Please increase node definition section.
- I don't use Auto Scaling Group, Because of several problems when terminating.

## Author
[snakaya](https://github.com/snakaya)

## License
<pre>
The MIT License (MIT)
=====================

Copyright (c) 2015 Panagis Tselentis

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
</pre>
