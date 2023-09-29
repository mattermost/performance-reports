### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ProductNoticesStore.ClearOldNotices | avg | 39ms | 139ms | 100ms | 258.00
| LinkMetadataStore.Save | avg | 15ms | 35ms | 20ms | 134.54
| CommandWebhookStore.Cleanup | avg | 43ms | 99ms | 56ms | 131.36
| StatusStore.UpdateExpiredDNDStatuses | avg | 19ms | 40ms | 21ms | 112.78
| TokenStore.Cleanup | avg | 46ms | 89ms | 43ms | 93.57
| PreferenceStore.DeleteCategoryAndName | avg | 25ms | 45ms | 20ms | 81.13
| StatusStore.SaveOrUpdate | avg | 110ms | 179ms | 69ms | 62.45
| RoleStore.ChannelHigherScopedPermissions | avg | 30ms | 46ms | 16ms | 54.12
| PostStore.GetPostReminders | avg | 48ms | 74ms | 26ms | 53.82
| PostStore.GetPostReminderMetadata | avg | 42ms | 63ms | 21ms | 50.31
| PostStore.AnalyticsPostCount | avg | 1.676s | 2.484s | 808ms | 48.22
| UserStore.Count | avg | 47ms | 63ms | 16ms | 33.78
| PluginStore.List | avg | 34ms | 44ms | 10ms | 28.99
| PreferenceStore.Save | avg | 43ms | 55ms | 12ms | 27.84
| PostAcknowledgementStore.GetForPost | avg | 31ms | 39ms | 8ms | 25.99
| ChannelStore.UpdateSidebarCategories | avg | 319ms | 399ms | 80ms | 25.08
| TeamStore.GetMember | avg | 10ms | 12ms | 2ms | 19.94
| UserStore.GetByUsername | avg | 43ms | 51ms | 8ms | 18.53
| ChannelStore.Save | avg | 128ms | 151ms | 23ms | 17.90
| ThreadStore.MarkAllAsReadByChannels | avg | 30ms | 35ms | 5ms | 16.65
| BotStore.Get | avg | 31ms | 36ms | 5ms | 16.07
| JobStore.UpdateStatus | avg | 21ms | 24ms | 3ms | 14.42
| ChannelStore.UpdateLastViewedAt | avg | 26ms | 29ms | 3ms | 11.39
| ReactionStore.Save | avg | 97ms | 107ms | 10ms | 10.30
| PostPersistentNotificationStore.DeleteExpired | avg | 19ms | 21ms | 2ms | 10.28
| StatusStore.GetByIds | avg | 49ms | 54ms | 5ms | 10.16
| JobStore.GetAllByStatus | avg | 43ms | 47ms | 4ms | 9.39
| PostPersistentNotificationStore.Get | avg | 21ms | 23ms | 2ms | 9.34
| ChannelStore.GetChannelUnread | avg | 61ms | 66ms | 5ms | 8.22
| PostStore.GetPostIdBeforeTime | avg | 24ms | 26ms | 2ms | 8.19
| ClusterDiscoveryStore.SetLastPingAt | avg | 25ms | 27ms | 2ms | 8.03
| ThreadStore.MarkAsRead | avg | 26ms | 28ms | 2ms | 7.78
| StatusStore.UpdateLastActivityAt | avg | 26ms | 28ms | 2ms | 7.67
| SessionStore.UpdateLastActivityAt | avg | 27ms | 29ms | 2ms | 7.44
| ThreadStore.MaintainMembership | avg | 60ms | 64ms | 4ms | 6.64
| FileInfoStore.Save | avg | 31ms | 33ms | 2ms | 6.49
| PostStore.Update | avg | 80ms | 85ms | 5ms | 6.28
| PostStore.Save | avg | 84ms | 89ms | 5ms | 5.98
| SessionStore.Get | avg | 34ms | 36ms | 2ms | 5.93
| ChannelStore.CreateInitialSidebarCategories | avg | 102ms | 108ms | 6ms | 5.91
| PostStore.SetPostReminder | avg | 91ms | 95ms | 4ms | 4.40
| ChannelStore.AutocompleteInTeamForSearch | avg | 251ms | 262ms | 11ms | 4.39
| ChannelStore.CreateDirectChannel | avg | 258ms | 269ms | 11ms | 4.26
| TeamStore.SaveMember | avg | 78ms | 80ms | 2ms | 2.58
| UserStore.Save | avg | 118ms | 121ms | 3ms | 2.55
| ProductNoticesStore.View | avg | 178ms | 182ms | 4ms | 2.24
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ProductNoticesStore.ClearOldNotices | p99 | 50ms | 248ms | 198ms | 397.89
| RoleStore.ChannelHigherScopedPermissions | p99 | 170ms | 472ms | 302ms | 177.15
| UserStore.GetByUsername | p99 | 248ms | 675ms | 427ms | 171.95
| LinkMetadataStore.Save | p99 | 88ms | 230ms | 142ms | 161.36
| PreferenceStore.DeleteCategoryAndName | p99 | 94ms | 238ms | 144ms | 153.19
| CommandWebhookStore.Cleanup | p99 | 99ms | 247ms | 148ms | 149.49
| TokenStore.Cleanup | p99 | 99ms | 247ms | 148ms | 149.49
| StatusStore.UpdateExpiredDNDStatuses | p99 | 97ms | 242ms | 145ms | 149.10
| ChannelStore.UpdateSidebarCategories | p99 | 977ms | 2.315s | 1.338s | 136.97
| StatusStore.SaveOrUpdate | p99 | 978ms | 2.27s | 1.292s | 132.16
| JobStore.UpdateStatus | p99 | 97ms | 223ms | 126ms | 129.76
| JobStore.UpdateStatusOptimistically | p99 | 96ms | 209ms | 113ms | 117.25
| PostPersistentNotificationStore.DeleteExpired | p99 | 97ms | 197ms | 100ms | 103.09
| UserStore.Count | p99 | 232ms | 468ms | 236ms | 101.73
| PostAcknowledgementStore.GetForPost | p99 | 236ms | 472ms | 236ms | 99.97
| ChannelStore.CreateSidebarCategory | p99 | 497ms | 990ms | 493ms | 99.10
| PostStore.GetPostReminderMetadata | p99 | 237ms | 458ms | 221ms | 93.25
| PostStore.GetPostReminders | p99 | 242ms | 448ms | 206ms | 85.21
| UserStore.Update | p99 | 246ms | 379ms | 133ms | 54.04
| FileInfoStore.SetContent | p99 | 248ms | 344ms | 96ms | 38.70
| TeamStore.GetMember | p99 | 98ms | 135ms | 37ms | 37.89
| ClusterDiscoveryStore.SetLastPingAt | p99 | 182ms | 217ms | 35ms | 19.27
| JobStore.GetAllByStatus | p99 | 382ms | 454ms | 72ms | 18.84
| PreferenceStore.Save | p99 | 377ms | 436ms | 59ms | 15.67
| UserStore.UpdateUpdateAt | p99 | 117ms | 132ms | 15ms | 12.83
| ChannelMemberHistoryStore.LogJoinEvent | p99 | 140ms | 154ms | 14ms | 10.01
| BotStore.Get | p99 | 217ms | 234ms | 17ms | 7.83
| PostStore.Update | p99 | 402ms | 433ms | 31ms | 7.71
| PluginStore.Delete | p99 | 144ms | 155ms | 11ms | 7.65
| ThreadStore.MarkAsRead | p99 | 194ms | 208ms | 14ms | 7.23
| PostStore.Save | p99 | 686ms | 734ms | 48ms | 6.99
| PostPriorityStore.GetForPost | p99 | 403ms | 430ms | 27ms | 6.70
| ThreadStore.GetTotalUnreadThreads | p99 | 290ms | 306ms | 16ms | 5.52
| PostStore.GetPostIdAfterTime | p99 | 156ms | 164ms | 8ms | 5.14
| StatusStore.UpdateLastActivityAt | p99 | 200ms | 210ms | 10ms | 5.00
| PostStore.GetPostIdBeforeTime | p99 | 203ms | 212ms | 9ms | 4.44
| ChannelStore.UpdateLastViewedAt | p99 | 204ms | 213ms | 9ms | 4.41
| SessionStore.UpdateLastActivityAt | p99 | 204ms | 213ms | 9ms | 4.40
| ChannelStore.CreateInitialSidebarCategories | p99 | 857ms | 894ms | 37ms | 4.32
| ThreadStore.MaintainMembership | p99 | 402ms | 419ms | 17ms | 4.23
| SessionStore.Remove | p99 | 216ms | 225ms | 9ms | 4.18
| ThreadStore.UpdateMembership | p99 | 195ms | 203ms | 8ms | 4.11
| UserStore.UpdateFailedPasswordAttempts | p99 | 184ms | 191ms | 7ms | 3.80
| SystemStore.GetByName | p99 | 188ms | 195ms | 7ms | 3.73
| FileInfoStore.Save | p99 | 219ms | 227ms | 8ms | 3.65
| GroupStore.AdminRoleGroupsForSyncableMember | p99 | 225ms | 233ms | 8ms | 3.56
| AuditStore.Save | p99 | 177ms | 183ms | 6ms | 3.39
| ReactionStore.Save | p99 | 478ms | 494ms | 16ms | 3.34
| PostPersistentNotificationStore.Get | p99 | 191ms | 197ms | 6ms | 3.14
| ThreadStore.MarkAllAsReadByChannels | p99 | 220ms | 226ms | 6ms | 2.73
| UserStore.GetUnreadCount | p99 | 356ms | 365ms | 9ms | 2.53
| StatusStore.GetByIds | p99 | 453ms | 464ms | 11ms | 2.43
| FileInfoStore.GetForPost | p99 | 476ms | 486ms | 10ms | 2.10
| ChannelStore.IncrementMentionCount | p99 | 201ms | 205ms | 4ms | 1.99
| ProductNoticesStore.View | p99 | 1.669s | 1.702s | 33ms | 1.98
| ChannelStore.GetChannelsByUser | p99 | 462ms | 471ms | 9ms | 1.95
| ChannelStore.GetSidebarCategoriesForTeamForUser | p99 | 734ms | 748ms | 14ms | 1.91
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | p99 | 480ms | 488ms | 8ms | 1.67
| ThreadStore.Get | p99 | 468ms | 475ms | 7ms | 1.49
| ThreadStore.GetTotalUnreadMentions | p99 | 335ms | 340ms | 5ms | 1.49
| TeamStore.SaveMember | p99 | 482ms | 488ms | 6ms | 1.24
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| PostPersistentNotificationStore.UpdateLastActivity | avg | 24ms | 0s | -24ms | -100.95
| TeamStore.GetMany | avg | 84ms | 0s | -84ms | -100.25
| PostStore.GetPostsByIds | avg | 60ms | 0s | -60ms | -100.24
| ChannelStore.GetChannelsByIds | avg | 106ms | 0s | -106ms | -99.56
| SessionStore.GetSessionsExpired | avg | 64ms | 18ms | -46ms | -71.36
| UserAccessTokenStore.GetByToken | avg | 62ms | 33ms | -29ms | -46.70
| UserStore.GetMany | avg | 37ms | 22ms | -15ms | -40.44
| ChannelStore.CreateSidebarCategory | avg | 471ms | 295ms | -176ms | -37.35
| ChannelStore.GetTeamChannels | avg | 151ms | 103ms | -48ms | -31.88
| ChannelStore.GetSidebarCategory | avg | 139ms | 104ms | -35ms | -25.18
| JobStore.Get | avg | 33ms | 25ms | -8ms | -24.10
| SessionStore.Remove | avg | 33ms | 25ms | -8ms | -23.90
| ChannelStore.Autocomplete | avg | 189ms | 144ms | -45ms | -23.75
| UserStore.AutocompleteUsersInChannel | avg | 245ms | 189ms | -56ms | -22.88
| PostStore.SearchPostsForUser | avg | 461ms | 373ms | -88ms | -19.09
| ThreadStore.MarkAllAsReadByTeam | avg | 48ms | 39ms | -9ms | -18.72
| PostStore.GetPostsAfter | avg | 62ms | 51ms | -11ms | -17.84
| PostStore.GetPostsSince | avg | 105ms | 89ms | -16ms | -15.31
| UserStore.Search | avg | 104ms | 89ms | -15ms | -14.42
| JobStore.GetCountByStatusAndType | avg | 39ms | 34ms | -5ms | -12.67
| PostStore.Delete | avg | 204ms | 179ms | -25ms | -12.24
| ChannelStore.GetMembers | avg | 550ms | 490ms | -60ms | -10.91
| PostPriorityStore.GetForPost | avg | 41ms | 37ms | -4ms | -9.79
| ReactionStore.GetForPost | avg | 52ms | 47ms | -5ms | -9.65
| WebhookStore.GetOutgoingByTeam | avg | 52ms | 47ms | -5ms | -9.64
| ThreadStore.GetThreadFollowers | avg | 42ms | 38ms | -4ms | -9.60
| ThreadStore.GetMembershipForUser | avg | 45ms | 41ms | -4ms | -8.99
| PostStore.GetPostsByThread | avg | 58ms | 53ms | -5ms | -8.60
| JobStore.UpdateStatusOptimistically | avg | 23ms | 21ms | -2ms | -8.56
| UserStore.GetAllProfilesInChannel | avg | 908ms | 835ms | -73ms | -8.04
| ThreadStore.GetTeamsUnreadForUser | avg | 51ms | 47ms | -4ms | -7.83
| ThreadStore.GetThreadForUser | avg | 78ms | 72ms | -6ms | -7.65
| ChannelStore.GetFileCount | avg | 40ms | 37ms | -3ms | -7.57
| ThreadStore.GetThreadUnreadReplyCount | avg | 66ms | 61ms | -5ms | -7.53
| SessionStore.GetSessionsWithActiveDeviceIds | avg | 41ms | 38ms | -3ms | -7.31
| ChannelStore.GetMember | avg | 27ms | 25ms | -2ms | -7.28
| JobStore.GetNewestJobByStatusesAndType | avg | 28ms | 26ms | -2ms | -7.19
| TeamStore.Get | avg | 43ms | 40ms | -3ms | -6.96
| ChannelStore.GetMemberCount | avg | 75ms | 70ms | -5ms | -6.67
| ChannelStore.Get | avg | 60ms | 56ms | -4ms | -6.65
| PostStore.GetSingle | avg | 46ms | 43ms | -3ms | -6.52
| LinkMetadataStore.Get | avg | 47ms | 44ms | -3ms | -6.33
| ChannelStore.GetMemberForPost | avg | 52ms | 49ms | -3ms | -5.72
| TeamStore.GetByName | avg | 36ms | 34ms | -2ms | -5.54
| GroupStore.GetGroups | avg | 38ms | 36ms | -2ms | -5.30
| ChannelStore.GetChannelsByUser | avg | 60ms | 57ms | -3ms | -5.00
| PostPersistentNotificationStore.GetSingle | avg | 41ms | 39ms | -2ms | -4.85
| UserStore.Update | avg | 62ms | 59ms | -3ms | -4.82
| PostStore.GetEtag | avg | 45ms | 43ms | -2ms | -4.45
| PreferenceStore.Get | avg | 46ms | 44ms | -2ms | -4.33
| ChannelStore.GetChannels | avg | 47ms | 45ms | -2ms | -4.27
| ChannelStore.GetMembersForUser | avg | 48ms | 46ms | -2ms | -4.15
| PostStore.GetPostsBefore | avg | 51ms | 49ms | -2ms | -3.92
| ThreadStore.GetThreadsForUser | avg | 55ms | 53ms | -2ms | -3.65
| PostAcknowledgementStore.GetForPosts | avg | 70ms | 68ms | -2ms | -2.88
| PostPriorityStore.GetForPosts | avg | 72ms | 70ms | -2ms | -2.78
| PostStore.Get | avg | 95ms | 93ms | -2ms | -2.11
| ChannelStore.GetPublicChannelsForTeam | avg | 100ms | 98ms | -2ms | -1.99
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| TeamStore.GetMany | p99 | 244ms | 0s | -244ms | -100.00
| ChannelStore.GetChannelsByIds | p99 | 490ms | 0s | -490ms | -100.00
| PostStore.GetPostsByIds | p99 | 245ms | 0s | -245ms | -99.80
| PostPersistentNotificationStore.UpdateLastActivity | p99 | 49ms | 0s | -49ms | -99.49
| SessionStore.GetSessionsExpired | p99 | 480ms | 49ms | -431ms | -89.79
| UserAccessTokenStore.GetByToken | p99 | 885ms | 225ms | -660ms | -74.57
| UserStore.GetMany | p99 | 235ms | 97ms | -138ms | -58.72
| ChannelStore.GetSidebarCategory | p99 | 3.15s | 1.39s | -1.76s | -55.86
| JobStore.UpdateOptimistically | p99 | 207ms | 98ms | -109ms | -52.78
| ChannelStore.Autocomplete | p99 | 1.742s | 882ms | -860ms | -49.37
| PluginStore.List | p99 | 770ms | 390ms | -380ms | -49.35
| UserStore.AutocompleteUsersInChannel | p99 | 1.87s | 955ms | -915ms | -48.94
| PostStore.Delete | p99 | 940ms | 492ms | -448ms | -47.66
| PostStore.SearchPostsForUser | p99 | 6.985s | 4.485s | -2.5s | -35.79
| TeamStore.GetByName | p99 | 366ms | 241ms | -125ms | -34.19
| JobStore.GetCountByStatusAndType | p99 | 347ms | 237ms | -110ms | -31.65
| ChannelStore.CreateDirectChannel | p99 | 1.837s | 1.295s | -542ms | -29.50
| PostStore.GetPostsSince | p99 | 821ms | 590ms | -231ms | -28.15
| ChannelStore.GetFileCount | p99 | 338ms | 249ms | -89ms | -26.30
| JobStore.Get | p99 | 228ms | 168ms | -60ms | -26.29
| PostStore.GetPostsAfter | p99 | 523ms | 401ms | -122ms | -23.33
| JobStore.Save | p99 | 205ms | 161ms | -44ms | -21.46
| UserStore.Search | p99 | 946ms | 744ms | -202ms | -21.34
| SessionStore.GetSessionsWithActiveDeviceIds | p99 | 368ms | 299ms | -69ms | -18.76
| UserStore.IsEmpty | p99 | 176ms | 144ms | -32ms | -18.21
| ThreadStore.GetThreadForUser | p99 | 623ms | 513ms | -110ms | -17.65
| UserStore.GetAllProfilesInChannel | p99 | 4.509s | 3.883s | -626ms | -13.88
| ChannelStore.GetGuestCount | p99 | 336ms | 290ms | -46ms | -13.68
| ReactionStore.GetForPost | p99 | 456ms | 395ms | -61ms | -13.39
| GroupStore.GetGroups | p99 | 371ms | 325ms | -46ms | -12.39
| TeamStore.Get | p99 | 409ms | 366ms | -43ms | -10.50
| ThreadStore.GetThreadFollowers | p99 | 386ms | 347ms | -39ms | -10.09
| UserStore.GetProfileByIds | p99 | 373ms | 336ms | -37ms | -9.92
| PostStore.GetSingle | p99 | 424ms | 385ms | -39ms | -9.21
| ChannelStore.AutocompleteInTeamForSearch | p99 | 2.13s | 1.94s | -190ms | -8.92
| LinkMetadataStore.Get | p99 | 427ms | 391ms | -36ms | -8.43
| PostStore.Get | p99 | 767ms | 707ms | -60ms | -7.82
| ChannelStore.GetMemberCount | p99 | 500ms | 462ms | -38ms | -7.61
| ChannelStore.GetPinnedPostCount | p99 | 381ms | 353ms | -28ms | -7.35
| WebhookStore.GetOutgoingByTeam | p99 | 460ms | 427ms | -33ms | -7.18
| ChannelStore.GetChannelsWithUnreadsAndWithMentions | p99 | 406ms | 377ms | -29ms | -7.14
| ChannelStore.GetMembersForUser | p99 | 436ms | 406ms | -30ms | -6.88
| GroupStore.GetByName | p99 | 231ms | 216ms | -15ms | -6.50
| TeamStore.GetChannelUnreadsForAllTeams | p99 | 266ms | 249ms | -17ms | -6.39
| PreferenceStore.Get | p99 | 427ms | 400ms | -27ms | -6.33
| PostStore.GetEtag | p99 | 433ms | 406ms | -27ms | -6.24
| ThreadStore.GetMembershipForUser | p99 | 423ms | 397ms | -26ms | -6.15
| ThreadStore.GetThreadUnreadReplyCount | p99 | 473ms | 446ms | -27ms | -5.71
| UserStore.GetProfilesByUsernames | p99 | 408ms | 385ms | -23ms | -5.64
| ThreadStore.GetTeamsUnreadForUser | p99 | 490ms | 464ms | -26ms | -5.30
| ChannelStore.Get | p99 | 489ms | 464ms | -25ms | -5.11
| UserStore.GetForLogin | p99 | 252ms | 240ms | -12ms | -4.77
| ChannelStore.GetChannels | p99 | 438ms | 418ms | -20ms | -4.57
| PostStore.GetPostsBefore | p99 | 439ms | 422ms | -17ms | -3.87
| StatusStore.Get | p99 | 220ms | 212ms | -8ms | -3.64
| ChannelStore.GetMemberForPost | p99 | 392ms | 378ms | -14ms | -3.57
| ChannelStore.GetMember | p99 | 236ms | 228ms | -8ms | -3.39
| ChannelStore.GetAllChannelMembersForUser | p99 | 200ms | 194ms | -6ms | -3.00
| PostStore.GetPostsByThread | p99 | 435ms | 422ms | -13ms | -2.99
| PostPersistentNotificationStore.GetSingle | p99 | 381ms | 370ms | -11ms | -2.89
| SessionStore.Save | p99 | 366ms | 356ms | -10ms | -2.73
| FileInfoStore.Get | p99 | 405ms | 394ms | -11ms | -2.72
| ChannelStore.GetTeamChannels | p99 | 488ms | 475ms | -13ms | -2.66
| ThreadStore.GetThreadsForUser | p99 | 457ms | 446ms | -11ms | -2.41
| FileInfoStore.AttachToPost | p99 | 310ms | 304ms | -6ms | -1.93
| ThreadStore.GetTotalThreads | p99 | 318ms | 312ms | -6ms | -1.88
| ChannelStore.SearchGroupChannels | p99 | 436ms | 430ms | -6ms | -1.38
| JobStore.GetNewestJobByStatusesAndType | p99 | 243ms | 240ms | -3ms | -1.23
| TeamStore.GetTeamsForUser | p99 | 252ms | 249ms | -3ms | -1.19
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| followThreadByUser | avg | 127ms | 225ms | 98ms | 76.95
| addChannelMember | avg | 1.349s | 1.549s | 200ms | 14.83
| getTeamMember | avg | 31ms | 35ms | 4ms | 12.90
| setPostReminder | avg | 349ms | 392ms | 43ms | 12.32
| updatePreferences | avg | 107ms | 114ms | 7ms | 6.55
| createUser | avg | 235ms | 250ms | 15ms | 6.38
| unfollowThreadByUser | avg | 210ms | 222ms | 12ms | 5.72
| getClientConfig | avg | 54ms | 57ms | 3ms | 5.53
| autocompleteChannelsForTeamForSearch | avg | 251ms | 262ms | 11ms | 4.38
| getUser | avg | 49ms | 51ms | 2ms | 4.07
| createDirectChannel | avg | 1.067s | 1.106s | 39ms | 3.65
| getChannel | avg | 87ms | 89ms | 2ms | 2.29
| getFileThumbnail | avg | 158ms | 161ms | 3ms | 1.90
| updateCategoriesForTeamForUser | avg | 634ms | 644ms | 10ms | 1.58
| viewChannel | avg | 153ms | 155ms | 2ms | 1.31
| saveReaction | avg | 256ms | 259ms | 3ms | 1.17
| getFilePreview | avg | 175ms | 177ms | 2ms | 1.14
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| logout | p99 | 981ms | 2.005s | 1.024s | 104.40
| unfollowThreadByUser | p99 | 995ms | 2.015s | 1.02s | 102.56
| addChannelMember | p99 | 4.839s | 6.101s | 1.262s | 26.08
| createGroupChannel | p99 | 7.175s | 8.563s | 1.388s | 19.35
| getProfileImage | p99 | 617ms | 728ms | 111ms | 17.98
| createUser | p99 | 1.578s | 1.712s | 134ms | 8.49
| getUsersByIds | p99 | 156ms | 166ms | 10ms | 6.41
| getUserStatusesByIds | p99 | 165ms | 175ms | 10ms | 6.06
| getChannel | p99 | 826ms | 856ms | 30ms | 3.63
| setPostReminder | p99 | 2.29s | 2.365s | 75ms | 3.28
| getClientConfig | p99 | 425ms | 438ms | 13ms | 3.06
| getUser | p99 | 470ms | 482ms | 12ms | 2.55
| followThreadByUser | p99 | 484ms | 495ms | 11ms | 2.27
| createDirectChannel | p99 | 4.627s | 4.732s | 105ms | 2.27
| getCategoriesForTeamForUser | p99 | 743ms | 758ms | 15ms | 2.02
| getUsers | p99 | 474ms | 481ms | 7ms | 1.48
| getFileThumbnail | p99 | 898ms | 911ms | 13ms | 1.45
| deletePost | p99 | 970ms | 984ms | 14ms | 1.44
| removeUserCustomStatus | p99 | 2.394s | 2.424s | 30ms | 1.25
| getFilePreview | p99 | 921ms | 931ms | 10ms | 1.09
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| patchPost | avg | 6.167s | 2.819s | -3.348s | -54.29
| createCategoryForTeamForUser | avg | 569ms | 344ms | -225ms | -39.54
| createChannel | avg | 151ms | 103ms | -48ms | -31.84
| searchAllChannels | avg | 192ms | 146ms | -46ms | -23.97
| autocompleteUsers | avg | 206ms | 162ms | -44ms | -21.39
| updateReadStateAllThreadsByUser | avg | 48ms | 39ms | -9ms | -18.61
| createPost | avg | 5.006s | 4.129s | -877ms | -17.52
| getPostsForChannel | avg | 664ms | 557ms | -107ms | -16.10
| searchPostsInTeam | avg | 611ms | 513ms | -98ms | -16.03
| searchUsers | avg | 107ms | 92ms | -15ms | -13.97
| getChannelMembersForTeamForUser | avg | 49ms | 46ms | -3ms | -6.14
| updateUserCustomStatus | avg | 714ms | 674ms | -40ms | -5.60
| getTeamsUnreadForUser | avg | 55ms | 52ms | -3ms | -5.44
| updateReadStateThreadByUser | avg | 529ms | 501ms | -28ms | -5.29
| deletePost | avg | 338ms | 321ms | -17ms | -5.02
| getChannelsForUser | avg | 60ms | 57ms | -3ms | -4.98
| getPublicChannelsForTeam | avg | 105ms | 100ms | -5ms | -4.78
| getChannelMember | avg | 69ms | 66ms | -3ms | -4.35
| getChannelsForTeamForUser | avg | 48ms | 46ms | -2ms | -4.19
| logout | avg | 339ms | 325ms | -14ms | -4.13
| getThreadsForUser | avg | 57ms | 55ms | -2ms | -3.52
| getPostThread | avg | 286ms | 276ms | -10ms | -3.49
| getPostsForChannelAroundLastUnread | avg | 162ms | 158ms | -4ms | -2.46
| removeUserCustomStatus | avg | 591ms | 580ms | -11ms | -1.86
| getChannelMembers | avg | 136ms | 134ms | -2ms | -1.47
| login | avg | 316ms | 312ms | -4ms | -1.27
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| updateCategoriesForTeamForUser | p99 | 8.15s | 2.431s | -5.719s | -70.17
| patchPost | p99 | 10s | 4.176s | -5.824s | -58.24
| searchAllChannels | p99 | 1.763s | 884ms | -879ms | -49.87
| autocompleteUsers | p99 | 1.663s | 940ms | -723ms | -43.47
| searchPostsInTeam | p99 | 8.348s | 4.929s | -3.419s | -40.95
| getPostsForChannel | p99 | 7.284s | 4.972s | -2.312s | -31.74
| searchUsers | p99 | 966ms | 769ms | -197ms | -20.39
| getTeamsUnreadForUser | p99 | 595ms | 497ms | -98ms | -16.48
| getChannelUnread | p99 | 658ms | 585ms | -73ms | -11.09
| autocompleteChannelsForTeamForSearch | p99 | 2.13s | 1.94s | -190ms | -8.92
| getChannelMembersForTeamForUser | p99 | 441ms | 412ms | -29ms | -6.58
| getPostsForChannelAroundLastUnread | p99 | 1.734s | 1.626s | -108ms | -6.23
| getUsersByNames | p99 | 419ms | 400ms | -19ms | -4.54
| getChannelsForTeamForUser | p99 | 443ms | 425ms | -18ms | -4.06
| getChannelStats | p99 | 497ms | 479ms | -18ms | -3.62
| createChannel | p99 | 488ms | 475ms | -13ms | -2.66
| getPublicChannelsForTeam | p99 | 496ms | 483ms | -13ms | -2.62
| getChannelMember | p99 | 496ms | 485ms | -11ms | -2.22
| getPreferences | p99 | 272ms | 266ms | -6ms | -2.21
| saveReaction | p99 | 1.908s | 1.875s | -33ms | -1.73
| createPost | p99 | 10s | 9.852s | -148ms | -1.48
| getTeamMembersForUser | p99 | 341ms | 336ms | -5ms | -1.47
| updateReadStateThreadByUser | p99 | 2.465s | 2.434s | -31ms | -1.26
| getThreadsForUser | p99 | 484ms | 478ms | -6ms | -1.24
| searchGroupChannels | p99 | 436ms | 431ms | -5ms | -1.15
| login | p99 | 2.397s | 2.37s | -27ms | -1.13
| getAllTeams | p99 | 281ms | 278ms | -3ms | -1.07
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 18ms| 19ms | 1ms | 5.524
| |  P99| 177ms| 183ms | 6ms | 3.388
| BotStore.Get |  Avg| 31ms| 36ms | 5ms | 16.071
| |  P99| 217ms| 234ms | 17ms | 7.834
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 14ms| 15ms | 1ms | 6.920
| |  P99| 140ms| 154ms | 14ms | 10.006
| ChannelStore.Autocomplete |  Avg| 189ms| 144ms | -45ms | -23.752
| |  P99| 1.742s| 882ms | -860ms | -49.366
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 251ms| 262ms | 11ms | 4.386
| |  P99| 2.13s| 1.94s | -190ms | -8.920
| ChannelStore.CreateDirectChannel |  Avg| 258ms| 269ms | 11ms | 4.256
| |  P99| 1.837s| 1.295s | -542ms | -29.503
| ChannelStore.CreateInitialSidebarCategories |  Avg| 102ms| 108ms | 6ms | 5.908
| |  P99| 857ms| 894ms | 37ms | 4.317
| ChannelStore.CreateSidebarCategory |  Avg| 471ms| 295ms | -176ms | -37.355
| |  P99| 497ms| 990ms | 493ms | 99.095
| ChannelStore.Get |  Avg| 60ms| 56ms | -4ms | -6.652
| |  P99| 489ms| 464ms | -25ms | -5.111
| ChannelStore.GetAllChannelMembersForUser |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 200ms| 194ms | -6ms | -2.997
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 83ms| 84ms | 1ms | 1.212
| |  P99| 480ms| 488ms | 8ms | 1.667
| ChannelStore.GetByName |  Avg| 22ms| 22ms | 0s | 0.000
| |  P99| 235ms| 233ms | -2ms | -0.852
| ChannelStore.GetChannelUnread |  Avg| 61ms| 66ms | 5ms | 8.219
| |  P99| 489ms| 491ms | 2ms | 0.409
| ChannelStore.GetChannels |  Avg| 47ms| 45ms | -2ms | -4.265
| |  P99| 438ms| 418ms | -20ms | -4.570
| ChannelStore.GetChannelsByIds |  Avg| 106ms| 0s | -106ms | -99.560
| |  P99| 490ms| 0s | -490ms | -100.000
| ChannelStore.GetChannelsByUser |  Avg| 60ms| 57ms | -3ms | -4.995
| |  P99| 462ms| 471ms | 9ms | 1.946
| ChannelStore.GetChannelsWithUnreadsAndWithMentions |  Avg| 43ms| 42ms | -1ms | -2.325
| |  P99| 406ms| 377ms | -29ms | -7.138
| ChannelStore.GetFileCount |  Avg| 40ms| 37ms | -3ms | -7.566
| |  P99| 338ms| 249ms | -89ms | -26.297
| ChannelStore.GetGuestCount |  Avg| 32ms| 32ms | 0s | 0.000
| |  P99| 336ms| 290ms | -46ms | -13.684
| ChannelStore.GetMember |  Avg| 27ms| 25ms | -2ms | -7.281
| |  P99| 236ms| 228ms | -8ms | -3.386
| ChannelStore.GetMemberCount |  Avg| 75ms| 70ms | -5ms | -6.670
| |  P99| 500ms| 462ms | -38ms | -7.607
| ChannelStore.GetMemberForPost |  Avg| 52ms| 49ms | -3ms | -5.719
| |  P99| 392ms| 378ms | -14ms | -3.569
| ChannelStore.GetMembers |  Avg| 550ms| 490ms | -60ms | -10.906
| |  P99| 2.388s| 2.393s | 5ms | 0.209
| ChannelStore.GetMembersForUser |  Avg| 48ms| 46ms | -2ms | -4.146
| |  P99| 436ms| 406ms | -30ms | -6.885
| ChannelStore.GetPinnedPostCount |  Avg| 40ms| 39ms | -1ms | -2.487
| |  P99| 381ms| 353ms | -28ms | -7.351
| ChannelStore.GetPublicChannelsForTeam |  Avg| 100ms| 98ms | -2ms | -1.994
| |  P99| 483ms| 481ms | -2ms | -0.414
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 87ms| 86ms | -1ms | -1.146
| |  P99| 734ms| 748ms | 14ms | 1.907
| ChannelStore.GetSidebarCategory |  Avg| 139ms| 104ms | -35ms | -25.180
| |  P99| 3.15s| 1.39s | -1.76s | -55.865
| ChannelStore.GetTeamChannels |  Avg| 151ms| 103ms | -48ms | -31.880
| |  P99| 488ms| 475ms | -13ms | -2.662
| ChannelStore.IncrementMentionCount |  Avg| 22ms| 23ms | 1ms | 4.554
| |  P99| 201ms| 205ms | 4ms | 1.987
| ChannelStore.InvalidateAllChannelMembersForUser |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.InvalidateChannelByName |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.Save |  Avg| 128ms| 151ms | 23ms | 17.900
| |  P99| 978ms| 975ms | -3ms | -0.307
| ChannelStore.SaveMember |  Avg| 152ms| 151ms | -1ms | -0.658
| |  P99| 1.017s| 1.025s | 8ms | 0.786
| ChannelStore.SearchGroupChannels |  Avg| 53ms| 53ms | 0s | 0.000
| |  P99| 436ms| 430ms | -6ms | -1.375
| ChannelStore.UpdateLastViewedAt |  Avg| 26ms| 29ms | 3ms | 11.387
| |  P99| 204ms| 213ms | 9ms | 4.412
| ChannelStore.UpdateSidebarCategories |  Avg| 319ms| 399ms | 80ms | 25.076
| |  P99| 977ms| 2.315s | 1.338s | 136.967
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 25ms| 26ms | 1ms | 4.062
| |  P99| 206ms| 206ms | 0s | 0.000
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 25ms| 27ms | 2ms | 8.032
| |  P99| 182ms| 217ms | 35ms | 19.273
| CommandWebhookStore.Cleanup |  Avg| 43ms| 99ms | 56ms | 131.363
| |  P99| 99ms| 247ms | 148ms | 149.494
| FileInfoStore.AttachToPost |  Avg| 51ms| 50ms | -1ms | -1.975
| |  P99| 310ms| 304ms | -6ms | -1.935
| FileInfoStore.Get |  Avg| 46ms| 46ms | 0s | 0.000
| |  P99| 405ms| 394ms | -11ms | -2.719
| FileInfoStore.GetForPost |  Avg| 56ms| 57ms | 1ms | 1.799
| |  P99| 476ms| 486ms | 10ms | 2.102
| FileInfoStore.Save |  Avg| 31ms| 33ms | 2ms | 6.489
| |  P99| 219ms| 227ms | 8ms | 3.648
| FileInfoStore.SetContent |  Avg| 57ms| 58ms | 1ms | 1.743
| |  P99| 248ms| 344ms | 96ms | 38.695
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 20ms| 21ms | 1ms | 5.010
| |  P99| 225ms| 233ms | 8ms | 3.561
| GroupStore.GetByName |  Avg| 19ms| 19ms | 0s | 0.000
| |  P99| 231ms| 216ms | -15ms | -6.499
| GroupStore.GetGroups |  Avg| 38ms| 36ms | -2ms | -5.304
| |  P99| 371ms| 325ms | -46ms | -12.394
| JobStore.Get |  Avg| 33ms| 25ms | -8ms | -24.096
| |  P99| 228ms| 168ms | -60ms | -26.286
| JobStore.GetAllByStatus |  Avg| 43ms| 47ms | 4ms | 9.387
| |  P99| 382ms| 454ms | 72ms | 18.842
| JobStore.GetCountByStatusAndType |  Avg| 39ms| 34ms | -5ms | -12.669
| |  P99| 347ms| 237ms | -110ms | -31.655
| JobStore.GetNewestJobByStatusesAndType |  Avg| 28ms| 26ms | -2ms | -7.186
| |  P99| 243ms| 240ms | -3ms | -1.233
| JobStore.Save |  Avg| 20ms| 21ms | 1ms | 5.007
| |  P99| 205ms| 161ms | -44ms | -21.463
| JobStore.UpdateOptimistically |  Avg| 21ms| 21ms | 0s | 0.000
| |  P99| 207ms| 98ms | -109ms | -52.777
| JobStore.UpdateStatus |  Avg| 21ms| 24ms | 3ms | 14.422
| |  P99| 97ms| 223ms | 126ms | 129.762
| JobStore.UpdateStatusOptimistically |  Avg| 23ms| 21ms | -2ms | -8.563
| |  P99| 96ms| 209ms | 113ms | 117.249
| LinkMetadataStore.Get |  Avg| 47ms| 44ms | -3ms | -6.333
| |  P99| 427ms| 391ms | -36ms | -8.432
| LinkMetadataStore.Save |  Avg| 15ms| 35ms | 20ms | 134.543
| |  P99| 88ms| 230ms | 142ms | 161.359
| PluginStore.Delete |  Avg| 14ms| 15ms | 1ms | 6.959
| |  P99| 144ms| 155ms | 11ms | 7.646
| PluginStore.List |  Avg| 34ms| 44ms | 10ms | 28.994
| |  P99| 770ms| 390ms | -380ms | -49.345
| PluginStore.SetWithOptions |  Avg| 31ms| 30ms | -1ms | -3.277
| |  P99| 239ms| 241ms | 2ms | 0.838
| PostAcknowledgementStore.GetForPost |  Avg| 31ms| 39ms | 8ms | 25.994
| |  P99| 236ms| 472ms | 236ms | 99.970
| PostAcknowledgementStore.GetForPosts |  Avg| 70ms| 68ms | -2ms | -2.877
| |  P99| 760ms| 756ms | -4ms | -0.526
| PostPersistentNotificationStore.DeleteExpired |  Avg| 19ms| 21ms | 2ms | 10.280
| |  P99| 97ms| 197ms | 100ms | 103.093
| PostPersistentNotificationStore.Get |  Avg| 21ms| 23ms | 2ms | 9.342
| |  P99| 191ms| 197ms | 6ms | 3.141
| PostPersistentNotificationStore.GetSingle |  Avg| 41ms| 39ms | -2ms | -4.852
| |  P99| 381ms| 370ms | -11ms | -2.888
| PostPersistentNotificationStore.UpdateLastActivity |  Avg| 24ms| 0s | -24ms | -100.947
| |  P99| 49ms| 0s | -49ms | -99.492
| PostPriorityStore.GetForPost |  Avg| 41ms| 37ms | -4ms | -9.793
| |  P99| 403ms| 430ms | 27ms | 6.700
| PostPriorityStore.GetForPosts |  Avg| 72ms| 70ms | -2ms | -2.785
| |  P99| 776ms| 773ms | -3ms | -0.387
| PostStore.AnalyticsPostCount |  Avg| 1.676s| 2.484s | 808ms | 48.220
| |  P99| 2.485s| 2.485s | 0s | 0.000
| PostStore.Delete |  Avg| 204ms| 179ms | -25ms | -12.242
| |  P99| 940ms| 492ms | -448ms | -47.659
| PostStore.Get |  Avg| 95ms| 93ms | -2ms | -2.106
| |  P99| 767ms| 707ms | -60ms | -7.824
| PostStore.GetEtag |  Avg| 45ms| 43ms | -2ms | -4.451
| |  P99| 433ms| 406ms | -27ms | -6.241
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 15ms| 16ms | 1ms | 6.648
| |  P99| 156ms| 164ms | 8ms | 5.138
| PostStore.GetPostIdBeforeTime |  Avg| 24ms| 26ms | 2ms | 8.190
| |  P99| 203ms| 212ms | 9ms | 4.444
| PostStore.GetPostReminderMetadata |  Avg| 42ms| 63ms | 21ms | 50.314
| |  P99| 237ms| 458ms | 221ms | 93.249
| PostStore.GetPostReminders |  Avg| 48ms| 74ms | 26ms | 53.817
| |  P99| 242ms| 448ms | 206ms | 85.212
| PostStore.GetPosts |  Avg| 25ms| 25ms | 0s | 0.000
| |  P99| 236ms| 234ms | -2ms | -0.849
| PostStore.GetPostsAfter |  Avg| 62ms| 51ms | -11ms | -17.841
| |  P99| 523ms| 401ms | -122ms | -23.325
| PostStore.GetPostsBefore |  Avg| 51ms| 49ms | -2ms | -3.924
| |  P99| 439ms| 422ms | -17ms | -3.874
| PostStore.GetPostsByIds |  Avg| 60ms| 0s | -60ms | -100.241
| |  P99| 245ms| 0s | -245ms | -99.796
| PostStore.GetPostsByThread |  Avg| 58ms| 53ms | -5ms | -8.596
| |  P99| 435ms| 422ms | -13ms | -2.987
| PostStore.GetPostsSince |  Avg| 105ms| 89ms | -16ms | -15.308
| |  P99| 821ms| 590ms | -231ms | -28.145
| PostStore.GetSingle |  Avg| 46ms| 43ms | -3ms | -6.522
| |  P99| 424ms| 385ms | -39ms | -9.208
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 84ms| 89ms | 5ms | 5.981
| |  P99| 686ms| 734ms | 48ms | 6.992
| PostStore.SearchPostsForUser |  Avg| 461ms| 373ms | -88ms | -19.092
| |  P99| 6.985s| 4.485s | -2.5s | -35.789
| PostStore.SetPostReminder |  Avg| 91ms| 95ms | 4ms | 4.397
| |  P99| 465ms| 466ms | 1ms | 0.215
| PostStore.Update |  Avg| 80ms| 85ms | 5ms | 6.283
| |  P99| 402ms| 433ms | 31ms | 7.714
| PreferenceStore.DeleteCategoryAndName |  Avg| 25ms| 45ms | 20ms | 81.131
| |  P99| 94ms| 238ms | 144ms | 153.189
| PreferenceStore.Get |  Avg| 46ms| 44ms | -2ms | -4.325
| |  P99| 427ms| 400ms | -27ms | -6.330
| PreferenceStore.GetAll |  Avg| 31ms| 31ms | 0s | 0.000
| |  P99| 249ms| 248ms | -1ms | -0.401
| PreferenceStore.Save |  Avg| 43ms| 55ms | 12ms | 27.844
| |  P99| 377ms| 436ms | 59ms | 15.670
| ProductNoticesStore.ClearOldNotices |  Avg| 39ms| 139ms | 100ms | 257.997
| |  P99| 50ms| 248ms | 198ms | 397.888
| ProductNoticesStore.View |  Avg| 178ms| 182ms | 4ms | 2.244
| |  P99| 1.669s| 1.702s | 33ms | 1.978
| ReactionStore.GetForPost |  Avg| 52ms| 47ms | -5ms | -9.651
| |  P99| 456ms| 395ms | -61ms | -13.386
| ReactionStore.Save |  Avg| 97ms| 107ms | 10ms | 10.297
| |  P99| 478ms| 494ms | 16ms | 3.345
| RoleStore.ChannelHigherScopedPermissions |  Avg| 30ms| 46ms | 16ms | 54.120
| |  P99| 170ms| 472ms | 302ms | 177.146
| RoleStore.GetByNames |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.Get |  Avg| 34ms| 36ms | 2ms | 5.928
| |  P99| 246ms| 248ms | 2ms | 0.814
| SessionStore.GetSessionsExpired |  Avg| 64ms| 18ms | -46ms | -71.355
| |  P99| 480ms| 49ms | -431ms | -89.789
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 41ms| 38ms | -3ms | -7.314
| |  P99| 368ms| 299ms | -69ms | -18.758
| SessionStore.Remove |  Avg| 33ms| 25ms | -8ms | -23.897
| |  P99| 216ms| 225ms | 9ms | 4.176
| SessionStore.Save |  Avg| 42ms| 41ms | -1ms | -2.375
| |  P99| 366ms| 356ms | -10ms | -2.729
| SessionStore.UpdateLastActivityAt |  Avg| 27ms| 29ms | 2ms | 7.440
| |  P99| 204ms| 213ms | 9ms | 4.404
| StatusStore.Get |  Avg| 18ms| 17ms | -1ms | -5.626
| |  P99| 220ms| 212ms | -8ms | -3.637
| StatusStore.GetByIds |  Avg| 49ms| 54ms | 5ms | 10.161
| |  P99| 453ms| 464ms | 11ms | 2.429
| StatusStore.SaveOrUpdate |  Avg| 110ms| 179ms | 69ms | 62.447
| |  P99| 978ms| 2.27s | 1.292s | 132.157
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 19ms| 40ms | 21ms | 112.784
| |  P99| 97ms| 242ms | 145ms | 149.100
| StatusStore.UpdateLastActivityAt |  Avg| 26ms| 28ms | 2ms | 7.667
| |  P99| 200ms| 210ms | 10ms | 4.999
| SystemStore.GetByName |  Avg| 19ms| 20ms | 1ms | 5.340
| |  P99| 188ms| 195ms | 7ms | 3.733
| TeamStore.Get |  Avg| 43ms| 40ms | -3ms | -6.957
| |  P99| 409ms| 366ms | -43ms | -10.502
| TeamStore.GetAllPage |  Avg| 27ms| 27ms | 0s | 0.000
| |  P99| 245ms| 244ms | -1ms | -0.409
| TeamStore.GetByName |  Avg| 36ms| 34ms | -2ms | -5.538
| |  P99| 366ms| 241ms | -125ms | -34.187
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 31ms| 30ms | -1ms | -3.264
| |  P99| 266ms| 249ms | -17ms | -6.386
| TeamStore.GetMany |  Avg| 84ms| 0s | -84ms | -100.249
| |  P99| 244ms| 0s | -244ms | -100.000
| TeamStore.GetMember |  Avg| 10ms| 12ms | 2ms | 19.944
| |  P99| 98ms| 135ms | 37ms | 37.891
| TeamStore.GetTeamsByUserId |  Avg| 29ms| 29ms | 0s | 0.000
| |  P99| 249ms| 248ms | -1ms | -0.402
| TeamStore.GetTeamsForUser |  Avg| 27ms| 27ms | 0s | 0.000
| |  P99| 252ms| 249ms | -3ms | -1.193
| TeamStore.SaveMember |  Avg| 78ms| 80ms | 2ms | 2.577
| |  P99| 482ms| 488ms | 6ms | 1.244
| ThreadStore.Get |  Avg| 47ms| 46ms | -1ms | -2.118
| |  P99| 468ms| 475ms | 7ms | 1.495
| ThreadStore.GetMembershipForUser |  Avg| 45ms| 41ms | -4ms | -8.985
| |  P99| 423ms| 397ms | -26ms | -6.150
| ThreadStore.GetTeamsUnreadForUser |  Avg| 51ms| 47ms | -4ms | -7.829
| |  P99| 490ms| 464ms | -26ms | -5.301
| ThreadStore.GetThreadFollowers |  Avg| 42ms| 38ms | -4ms | -9.600
| |  P99| 386ms| 347ms | -39ms | -10.093
| ThreadStore.GetThreadForUser |  Avg| 78ms| 72ms | -6ms | -7.645
| |  P99| 623ms| 513ms | -110ms | -17.654
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 66ms| 61ms | -5ms | -7.531
| |  P99| 473ms| 446ms | -27ms | -5.706
| ThreadStore.GetThreadsForUser |  Avg| 55ms| 53ms | -2ms | -3.650
| |  P99| 457ms| 446ms | -11ms | -2.407
| ThreadStore.GetTotalThreads |  Avg| 32ms| 32ms | 0s | 0.000
| |  P99| 318ms| 312ms | -6ms | -1.885
| ThreadStore.GetTotalUnreadMentions |  Avg| 33ms| 33ms | 0s | 0.000
| |  P99| 335ms| 340ms | 5ms | 1.490
| ThreadStore.GetTotalUnreadThreads |  Avg| 31ms| 31ms | 0s | 0.000
| |  P99| 290ms| 306ms | 16ms | 5.516
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 32ms| 32ms | 0s | 0.000
| |  P99| 326ms| 324ms | -2ms | -0.614
| ThreadStore.MaintainMembership |  Avg| 60ms| 64ms | 4ms | 6.639
| |  P99| 402ms| 419ms | 17ms | 4.228
| ThreadStore.MarkAllAsReadByChannels |  Avg| 30ms| 35ms | 5ms | 16.650
| |  P99| 220ms| 226ms | 6ms | 2.728
| ThreadStore.MarkAllAsReadByTeam |  Avg| 48ms| 39ms | -9ms | -18.716
| |  P99| 99ms| 98ms | -1ms | -1.010
| ThreadStore.MarkAsRead |  Avg| 26ms| 28ms | 2ms | 7.781
| |  P99| 194ms| 208ms | 14ms | 7.234
| ThreadStore.UpdateMembership |  Avg| 26ms| 27ms | 1ms | 3.887
| |  P99| 195ms| 203ms | 8ms | 4.111
| TokenStore.Cleanup |  Avg| 46ms| 89ms | 43ms | 93.567
| |  P99| 99ms| 247ms | 148ms | 149.494
| UserAccessTokenStore.GetByToken |  Avg| 62ms| 33ms | -29ms | -46.699
| |  P99| 885ms| 225ms | -660ms | -74.574
| UserStore.AutocompleteUsersInChannel |  Avg| 245ms| 189ms | -56ms | -22.876
| |  P99| 1.87s| 955ms | -915ms | -48.935
| UserStore.Count |  Avg| 47ms| 63ms | 16ms | 33.777
| |  P99| 232ms| 468ms | 236ms | 101.728
| UserStore.Get |  Avg| 26ms| 27ms | 1ms | 3.904
| |  P99| 245ms| 244ms | -1ms | -0.408
| UserStore.GetAllProfiles |  Avg| 24ms| 24ms | 0s | 0.000
| |  P99| 233ms| 232ms | -1ms | -0.429
| UserStore.GetAllProfilesInChannel |  Avg| 908ms| 835ms | -73ms | -8.039
| |  P99| 4.509s| 3.883s | -626ms | -13.884
| UserStore.GetByUsername |  Avg| 43ms| 51ms | 8ms | 18.534
| |  P99| 248ms| 675ms | 427ms | 171.955
| UserStore.GetForLogin |  Avg| 25ms| 24ms | -1ms | -3.982
| |  P99| 252ms| 240ms | -12ms | -4.765
| UserStore.GetMany |  Avg| 37ms| 22ms | -15ms | -40.440
| |  P99| 235ms| 97ms | -138ms | -58.723
| UserStore.GetProfileByIds |  Avg| 40ms| 39ms | -1ms | -2.476
| |  P99| 373ms| 336ms | -37ms | -9.915
| UserStore.GetProfilesByUsernames |  Avg| 45ms| 44ms | -1ms | -2.201
| |  P99| 408ms| 385ms | -23ms | -5.641
| UserStore.GetUnreadCount |  Avg| 42ms| 41ms | -1ms | -2.357
| |  P99| 356ms| 365ms | 9ms | 2.527
| UserStore.IsEmpty |  Avg| 11ms| 10ms | -1ms | -8.984
| |  P99| 176ms| 144ms | -32ms | -18.209
| UserStore.Save |  Avg| 118ms| 121ms | 3ms | 2.549
| |  P99| 486ms| 489ms | 3ms | 0.617
| UserStore.Search |  Avg| 104ms| 89ms | -15ms | -14.421
| |  P99| 946ms| 744ms | -202ms | -21.344
| UserStore.Update |  Avg| 62ms| 59ms | -3ms | -4.815
| |  P99| 246ms| 379ms | 133ms | 54.043
| UserStore.UpdateFailedPasswordAttempts |  Avg| 20ms| 21ms | 1ms | 5.006
| |  P99| 184ms| 191ms | 7ms | 3.804
| UserStore.UpdateUpdateAt |  Avg| 15ms| 16ms | 1ms | 6.651
| |  P99| 117ms| 132ms | 15ms | 12.827
| UserTermsOfServiceStore.GetByUser |  Avg| 26ms| 26ms | 0s | 0.000
| |  P99| 242ms| 244ms | 2ms | 0.826
| WebhookStore.GetOutgoingByTeam |  Avg| 52ms| 47ms | -5ms | -9.642
| |  P99| 460ms| 427ms | -33ms | -7.180
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 1.349s| 1.549s | 200ms | 14.830
| | P99| 4.839s| 6.101s | 1.262s | 26.078
| addTeamMember | Avg| 2.396s| 2.407s | 11ms | 0.459
| | P99| 10s| 10s | 0s | 0.000
| autocompleteChannelsForTeamForSearch | Avg| 251ms| 262ms | 11ms | 4.380
| | P99| 2.13s| 1.94s | -190ms | -8.920
| autocompleteUsers | Avg| 206ms| 162ms | -44ms | -21.391
| | P99| 1.663s| 940ms | -723ms | -43.467
| createCategoryForTeamForUser | Avg| 569ms| 344ms | -225ms | -39.542
| | P99| 995ms| 990ms | -5ms | -0.503
| createChannel | Avg| 151ms| 103ms | -48ms | -31.844
| | P99| 488ms| 475ms | -13ms | -2.662
| createDirectChannel | Avg| 1.067s| 1.106s | 39ms | 3.653
| | P99| 4.627s| 4.732s | 105ms | 2.269
| createGroupChannel | Avg| 1.8s| 1.798s | -2ms | -0.111
| | P99| 7.175s| 8.563s | 1.388s | 19.345
| createPost | Avg| 5.006s| 4.129s | -877ms | -17.518
| | P99| 10s| 9.852s | -148ms | -1.480
| createUser | Avg| 235ms| 250ms | 15ms | 6.382
| | P99| 1.578s| 1.712s | 134ms | 8.492
| deletePost | Avg| 338ms| 321ms | -17ms | -5.023
| | P99| 970ms| 984ms | 14ms | 1.443
| followThreadByUser | Avg| 127ms| 225ms | 98ms | 76.954
| | P99| 484ms| 495ms | 11ms | 2.271
| getAllTeams | Avg| 30ms| 30ms | 0s | 0.000
| | P99| 281ms| 278ms | -3ms | -1.067
| getCategoriesForTeamForUser | Avg| 88ms| 87ms | -1ms | -1.134
| | P99| 743ms| 758ms | 15ms | 2.018
| getChannel | Avg| 87ms| 89ms | 2ms | 2.292
| | P99| 826ms| 856ms | 30ms | 3.633
| getChannelMember | Avg| 69ms| 66ms | -3ms | -4.348
| | P99| 496ms| 485ms | -11ms | -2.218
| getChannelMembers | Avg| 136ms| 134ms | -2ms | -1.465
| | P99| 248ms| 249ms | 1ms | 0.404
| getChannelMembersForTeamForUser | Avg| 49ms| 46ms | -3ms | -6.136
| | P99| 441ms| 412ms | -29ms | -6.583
| getChannelStats | Avg| 41ms| 40ms | -1ms | -2.453
| | P99| 497ms| 479ms | -18ms | -3.622
| getChannelUnread | Avg| 73ms| 74ms | 1ms | 1.379
| | P99| 658ms| 585ms | -73ms | -11.088
| getChannelsForTeamForUser | Avg| 48ms| 46ms | -2ms | -4.193
| | P99| 443ms| 425ms | -18ms | -4.062
| getChannelsForUser | Avg| 60ms| 57ms | -3ms | -4.976
| | P99| 467ms| 471ms | 4ms | 0.856
| getClientConfig | Avg| 54ms| 57ms | 3ms | 5.533
| | P99| 425ms| 438ms | 13ms | 3.056
| getFilePreview | Avg| 175ms| 177ms | 2ms | 1.145
| | P99| 921ms| 931ms | 10ms | 1.086
| getFileThumbnail | Avg| 158ms| 161ms | 3ms | 1.896
| | P99| 898ms| 911ms | 13ms | 1.448
| getPostThread | Avg| 286ms| 276ms | -10ms | -3.492
| | P99| 2.204s| 2.225s | 21ms | 0.953
| getPostsForChannel | Avg| 664ms| 557ms | -107ms | -16.103
| | P99| 7.284s| 4.972s | -2.312s | -31.739
| getPostsForChannelAroundLastUnread | Avg| 162ms| 158ms | -4ms | -2.462
| | P99| 1.734s| 1.626s | -108ms | -6.227
| getPreferences | Avg| 32ms| 32ms | 0s | 0.000
| | P99| 272ms| 266ms | -6ms | -2.209
| getProfileImage | Avg| 114ms| 113ms | -1ms | -0.879
| | P99| 617ms| 728ms | 111ms | 17.977
| getPublicChannelsForTeam | Avg| 105ms| 100ms | -5ms | -4.784
| | P99| 496ms| 483ms | -13ms | -2.621
| getTeamMember | Avg| 31ms| 35ms | 4ms | 12.902
| | P99| 235ms| 235ms | 0s | 0.000
| getTeamMembersForUser | Avg| 31ms| 32ms | 1ms | 3.204
| | P99| 341ms| 336ms | -5ms | -1.467
| getTeamsForUser | Avg| 30ms| 29ms | -1ms | -3.387
| | P99| 250ms| 251ms | 1ms | 0.400
| getTeamsUnreadForUser | Avg| 55ms| 52ms | -3ms | -5.435
| | P99| 595ms| 497ms | -98ms | -16.481
| getThreadsForUser | Avg| 57ms| 55ms | -2ms | -3.518
| | P99| 484ms| 478ms | -6ms | -1.240
| getUser | Avg| 49ms| 51ms | 2ms | 4.074
| | P99| 470ms| 482ms | 12ms | 2.554
| getUserStatus | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 7ms| 7ms | 0s | 0.000
| | P99| 165ms| 175ms | 10ms | 6.064
| getUsers | Avg| 54ms| 55ms | 1ms | 1.861
| | P99| 474ms| 481ms | 7ms | 1.475
| getUsersByIds | Avg| 8ms| 8ms | 0s | 0.000
| | P99| 156ms| 166ms | 10ms | 6.413
| getUsersByNames | Avg| 47ms| 46ms | -1ms | -2.143
| | P99| 419ms| 400ms | -19ms | -4.538
| getWebappPlugins | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| login | Avg| 316ms| 312ms | -4ms | -1.266
| | P99| 2.397s| 2.37s | -27ms | -1.126
| logout | Avg| 339ms| 325ms | -14ms | -4.133
| | P99| 981ms| 2.005s | 1.024s | 104.401
| patchPost | Avg| 6.167s| 2.819s | -3.348s | -54.288
| | P99| 10s| 4.176s | -5.824s | -58.240
| removeUserCustomStatus | Avg| 591ms| 580ms | -11ms | -1.860
| | P99| 2.394s| 2.424s | 30ms | 1.253
| root | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| saveReaction | Avg| 256ms| 259ms | 3ms | 1.172
| | P99| 1.908s| 1.875s | -33ms | -1.729
| searchAllChannels | Avg| 192ms| 146ms | -46ms | -23.967
| | P99| 1.763s| 884ms | -879ms | -49.870
| searchGroupChannels | Avg| 53ms| 53ms | 0s | 0.000
| | P99| 436ms| 431ms | -5ms | -1.146
| searchPostsInTeam | Avg| 611ms| 513ms | -98ms | -16.030
| | P99| 8.348s| 4.929s | -3.419s | -40.955
| searchUsers | Avg| 107ms| 92ms | -15ms | -13.973
| | P99| 966ms| 769ms | -197ms | -20.387
| setPostReminder | Avg| 349ms| 392ms | 43ms | 12.321
| | P99| 2.29s| 2.365s | 75ms | 3.275
| unfollowThreadByUser | Avg| 210ms| 222ms | 12ms | 5.716
| | P99| 995ms| 2.015s | 1.02s | 102.563
| updateCategoriesForTeamForUser | Avg| 634ms| 644ms | 10ms | 1.577
| | P99| 8.15s| 2.431s | -5.719s | -70.168
| updatePreferences | Avg| 107ms| 114ms | 7ms | 6.546
| | P99| 487ms| 490ms | 3ms | 0.616
| updateReadStateAllThreadsByUser | Avg| 48ms| 39ms | -9ms | -18.612
| | P99| 99ms| 98ms | -1ms | -1.010
| updateReadStateThreadByUser | Avg| 529ms| 501ms | -28ms | -5.289
| | P99| 2.465s| 2.434s | -31ms | -1.257
| updateUserCustomStatus | Avg| 714ms| 674ms | -40ms | -5.602
| | P99| 2.45s| 2.447s | -3ms | -0.122
| uploadFileStream | Avg| 663ms| 663ms | 0s | 0.000
| | P99| 2.434s| 2.448s | 14ms | 0.575
| viewChannel | Avg| 153ms| 155ms | 2ms | 1.305
| | P99| 973ms| 964ms | -9ms | -0.925
